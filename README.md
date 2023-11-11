# Astro Starter Kit: Basics

This is a starter template for [Astro](https://astro.build), with the required files to deploy the website to [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview).

```
npm create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![basics](https://user-images.githubusercontent.com/4677417/186188965-73453154-fdec-4d6b-9c34-cb35c248ae5b.png)


## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                | Action                                           |
| :--------------------- | :----------------------------------------------- |
| `npm install`          | Installs dependencies                            |
| `npm run dev`          | Starts local dev server at `localhost:4321`      |
| `npm run build`        | Build your production site to `./dist/`          |
| `npm run preview`      | Preview your build locally, before deploying     |
| `npm run astro ...`    | Run CLI commands like `astro add`, `astro check` |
| `npm run astro --help` | Get help using the Astro CLI                     |
| `npm run swa:start`    | Starts local dev server using the SWA emulator   |
| `npm run swa:deploy`   | Deploy your site to Azure Static Web Apps        |
| `npm run swa:login`    | Login to Azure Static Web Apps                   |

## Configure CI/CD using GitHub Actions

This starter kit includes a GitHub Actions workflow template that builds and deploys your site to Azure Static Web Apps. To use it, you'll need to:

1. Rename the `azure-static-web-apps.yml.template` file in the `.github/workflows/` directory to `azure-static-web-apps.yml`.
2. Create a new Azure Static Web Apps instance (e.g.using the [Azure Portal](https://portal.azure.com)).
3. Create or update the `AZURE_STATIC_WEB_APPS_API_TOKEN` secret in your repository's settings with the API token from your Azure Static Web Apps instance. You can find this token in the Azure Portal under the Static Web Apps instance > **Manage deployment token**.

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
