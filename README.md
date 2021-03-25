# Nuxt Default Quickstart
> Starter template for a Nuxt project using the default setup

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/nuxt-default-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/nuxt-default-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)


This project uses Yarn, JavaScript (no TS), Vue templates and server-side rendering using Node.

There is just one page - [index.vue](/pages/index.vue).


## Preview

<div align="center">
    <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" width="400" />
</div>


## Installation

Install dependencies

```sh
$ yarn install
```


## Usage

Serve with hot reload at localhost:3000

```sh
$ yarn dev
```


## Deploy

Build for production and then launch server.

```sh
$ yarn build
$ yarn start
```

Generate static project to `dist` directory.

```sh
$ yarn generate
```

This can be deployed as a GitHub Pages site. 

Recommended:

- Add a `deploy` command to `package.json` as per docs.
- Or use GitHub Actions to build the site and commit the site to `gh-pages` branch.

See info on [GitHub Pages deployment](https://nuxtjs.org/docs/2.x/deployment/github-pages/) in the Nuxt docs.

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).


## How this project was generated

```sh
$ yarn create nuxt-app nuxt-default-quickstart
```

All the default options were used:

```
✨  Generating Nuxt.js project in nuxt-default-quickstart
? Project name: nuxt-default-quickstart
? Programming language: JavaScript
? Package manager: Yarn
? UI framework: None
? Nuxt.js modules: (Press <space> to select, <a> to toggle all, <i> to invert selection)
? Linting tools: (Press <space> to select, <a> to toggle all, <i> to invert selection)
? Testing framework: None
? Rendering mode: Universal (SSR / SSG)
? Deployment target: Server (Node.js hosting)
? Development tools: (Press <space> to select, <a> to toggle all, <i> to invert selection)
? What is your GitHub username? michaelcurrin
? Version control system: Git
```

Username was lowercased even though entered as `MichaelCurrin`.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
