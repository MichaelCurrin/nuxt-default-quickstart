# Nuxt Default Quickstart
> Starter template for a Nuxt project using the default setup

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/nuxt-default-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/nuxt-default-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node.js](https://img.shields.io/badge/Node.js->%3D12-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->%3D1-blue?logo=yarn&logoColor=white)](https://yarnpkg.com/)

[![dependency - nuxt](https://img.shields.io/badge/dependency-nuxt-blue)](https://www.npmjs.com/package/nuxt)

This project uses Yarn, JavaScript (no TS), Vue, Vue templates and server-side rendering using Node.

Content is in the [pages](/pages/) directory as `.vue` files.


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


## Start a fresh project

See the [Getting Started / Installation](https://nuxtjs.org/docs/2.x/get-started/installation) Nuxt docs for more info.

This project was generated with this command:

```sh
$ yarn create nuxt-app nuxt-default-quickstart
```

All the default options were used, as follows:

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

Username became lowercase even though entered as `MichaelCurrin`. The app suggested `Michael Currin`, perhaps from git name rather. I don't know how this gets used.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
