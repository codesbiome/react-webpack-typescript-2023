# React Webpack Typescript (RWT)

React Webpack Typescript Boilerplate with custom webpack configurations for hot reloading.

A minimal secure boilerplate for writing Web Applications using [React](https://reactjs.org/), [Webpack](https://webpack.js.org/) & [TypeScript](https://www.typescriptlang.org/). <br /> This project makes use of latest packages and configurations to serve the best environment for development.

<br>

## Screenshot

<img src="assets/images/screenshot.png" />

<br>

## Core Features

- ⚛️ React
- 🌀 TypeScript
- 🥗 SASS/SCSS Loader
- 🛶 LESS Loader (optional)
- 🎨 CSS Loader
- 📸 Image Loader
- 🆎 Font Loader
- 🧹 ESLint
- 🔱 Webpack & Configuration
- 🧩 Aliases for Project Paths
- 🔥 React Fast Refresh + Webpack HMR
- 🌞 Dark Mode + Light Mode (Theme)

<br />

## Installation

#### To install this boilerplate you need to run following commands

<br>

Clone the repository :

```bash
git clone https://github.com/codesbiome/react-webpack-typescript-2022
```

<br>

Install dependencies using Yarn or NPM or PNPM :

```bash
# using pnpm
pnpm install

# or using yarn
yarn install

# or using npm
npm install
```

<br />

## Start : Development

To develop and run your web application, you need to run following command :

```bash
yarn start
```

<br />

## Lint : Development

To lint application source code using ESLint via this command :

```bash
yarn lint
```

<br />

## Build : Production

Distribution files output will be generated in `dist/` directory by default.

To build the production ready files for distribution, use the following command :

```bash
yarn build
```

<br />

## Serve : Production

Serve helps you serve a static site, single page application or just a static file. It also provides a neat interface for listing the directory's contents. This command serves build files from `dist/` directory.

```bash
yarn serve
```

<br />

## Webpack Configurations

To make it easier for managing environment based webpack configurations, we using separated `development` and `production` configuration files, they are available in :

```bash
# Development webpack config
tools/webpack/webpack.config.dev.js

# Production webpack config
tools/webpack/webpack.config.prod.js
```

For further information, you can visit [Webpack Configuration](https://webpack.js.org/configuration/)
