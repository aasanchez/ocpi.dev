# OCPI Development Platform

[![Netlify Status](https://api.netlify.com/api/v1/badges/4d8ebf71-99de-497c-81bb-a1d028ae95d4/deploy-status)](https://app.netlify.com/sites/preeminent-kulfi-e11c7e/deploys)

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

## Installation

```shell
yarn
```

## Local Development

```shell
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without
having to restart the server.

### Build

```shell
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```shell
USE_SSH=true yarn deploy
```

Not using SSH:

```shell
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the
`gh-pages` branch.
