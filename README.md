
# Vue.JS + Typescript + Three.JS Boilerplate?

Need info?
| or [Create an issue](https://github.com/NezaelHD/vue3-typescript-threejs-boilerplate/issues/new)
| Check [our project Board](https://github.com/NezaelHD/vue3-typescript-threejs-boilerplate/projects/3)

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/license/mit)

---

## Table of Contents

- [Getting Started](#getting-started)
    - [Project description](#project-description)
    - [Prerequisites](#prerequisites)
    - [Cloning and starting the project](#cloning-and-starting-the-project)
- [About the project](#about-the-project)
    - [Features](#features)
- [How to contribute](#how-to-contribute)

## Getting started

### Project description

This project was made in order to simplify the start of a vue.js and three.js project. As they were not boilerplate available for this kind of technology, i decided to make one.

### Prerequisites

This project uses the Yarn package manager to add dependencies and install them.
Download the following software here :

<a href="https://yarnpkg.com/">
  <img src="https://seeklogo.com/images/Y/yarn-logo-F5E7A65FA2-seeklogo.com.png" alt="Yarn" width="100" height="100">
</a>

If you want, you can also use Docker with this application. It is not currently supported but you can make a PR to implement it.

### Cloning and starting the project

If you want to start using this boilerplate you can clone the repo using this command :
```bash
git clone git@github.com:NezaelHD/vue3-typescript-threejs-boilerplate.git
```

In order to install all needed packages, launch the following command :
```bash
yarn install
```

You are now ready to develop you own project thank's to the boilerplate.

## About the project

### Features

Here are the differents commands available in the project :

-  `yarn dev` : Start a local web server in order to refresh the project when you make modifications in files.
- `yarn build` : Generate a fresh build ready for production
- `yarn preview` : Start a local web server that serves the built solution from the `/dist`folder
- `yarn lint`: Check all the `.ts` and `.vue`file in the project to fix them in order to have a good code quality.

This project is using a GitHub Action for prettier so if you forgot to launch the `yarn lint`command, it will launch it for you when you will commit and push the differents fixes made.
[Here is the link to the used GitHub Action which was made by a person of the community.](https://github.com/marketplace/actions/prettier-action)

Here are the differents technology used by the project :

<a href="https://www.typescriptlang.org/">
<img src="https://grafikart.fr/uploads/icons/typescript.svg" alt="TypeScript" width="100" height="100">
</a>
<a href="https://vuejs.org/">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/langfr-440px-Vue.js_Logo_2.svg.png" alt="Vue.JS" width="100" height="100">
</a>
<a href="https://threejs.org/">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3f/Three.js_Icon.svg/440px-Three.js_Icon.svg.png" alt="Three.JS" width="100" height="100">
</a>
<a href="https://vitejs.dev/">
<img src="https://grafikart.fr/uploads/icons/vitejs.svg" alt="Vite" width="100" height="100">
</a>
<a href="https://prettier.io/">
<img src="https://raw.githubusercontent.com/prettier/prettier-logo/master/images/prettier-icon-light.png" alt="Prettier" width="100" height="100">
</a>
<a href="https://sass-lang.com/">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Sass_Logo_Color.svg/262px-Sass_Logo_Color.svg.png" alt="Sass" width="100" height="100">
</a>


## How to contribute

If you have some ideas, you can submit them by creating issues here:
[Create an issue](https://github.com/NezaelHD/choco-cnam/issues/new)

If you want to maintain this boilerplate, you can also fork the project and then make the modifications you want. Once done make a pull request and i will review it and then if it is all good i will merge it.
