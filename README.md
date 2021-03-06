# Figma Plugin Material-UI React Template

![Logo](https://github.com/gsajith/figma-plugin-material-ui-template/blob/master/Logo.png?raw=true)

Based on [nirsky/Figma Plugin React Template](https://github.com/nirsky/figma-plugin-react-template) but with [Material-UI](https://material-ui.com/) added.

This template contains the React example as shown on [Figma Docs](https://www.figma.com/plugin-docs/intro/), with some structural changes and extra tooling. This template also adds examples for how to use Material-UI's theming and components.

## Quickstart
* Run `yarn` to install dependencies.
* Run `yarn build:watch` to start webpack in watch mode.
* Open `Figma` -> `Plugins` -> `Development` -> `New Plugin...` and choose `manifest.json` file from this repo.

⭐ To change the UI of your plugin (the react code), start editing [App.tsx](./src/app/components/App.tsx).
⭐ To interact with the Figma API edit [controller.ts](./src/plugin/controller.ts).
⭐ Read more on the [Figma API Overview](https://www.figma.com/plugin-docs/api/api-overview/).

## Toolings
This repo is using:
* React + Webpack
* Material-UI
* TypeScript
* Prettier precommit hook
