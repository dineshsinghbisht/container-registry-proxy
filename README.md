# Container Registry Proxy

[![GitHub stars](https://img.shields.io/github/stars/Addono/container-registry-proxy?style=for-the-badge)](https://github.com/Addono/container-registry-proxy/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Addono/container-registry-proxy?style=for-the-badge)](https://github.com/Addono/container-registry-proxy/network)
[![GitHub issues](https://img.shields.io/github/issues/Addono/container-registry-proxy?style=for-the-badge)](https://github.com/Addono/container-registry-proxy/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Addono/container-registry-proxy?style=for-the-badge)](https://github.com/Addono/container-registry-proxy/pulls)
[![GitHub license](https://img.shields.io/github/license/Addono/container-registry-proxy?style=for-the-badge)](https://github.com/Addono/container-registry-proxy/blob/master/LICENSE)
[![npm](https://img.shields.io/npm/dw/container-registry-proxy?style=for-the-badge)](https://www.npmjs.com/package/container-registry-proxy)
[![npm](https://img.shields.io/npm/v/container-registry-proxy?style=for-the-badge)](https://www.npmjs.com/package/container-registry-proxy)

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Running the Tests](#tests)
- [Deployment](#deployment)
- [Usage](#usage)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>

The Container Registry Proxy is a small proxy for communicating with a container registry. The end-goal of the project is to allow alternating traffic in-transit as to facilitate chaos engineering.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

You need to have [Yarn](https://yarnpkg.com/en/docs/install) installed to use this repository.

### Installing

First we need to install all dependencies, run:

```bash
yarn install
```

To start the development environment, run:

```bash
# Without file watching
yarn start

# With file watching
yarn dev
```


## 🔧 Running the Tests <a name = "tests"></a>

After setting up the development environment, tests can be invoked using:

```bash
yarn test
```

## 🎈 Usage <a name="usage"></a>

Execute:

```bash
yarn build
```

Which builds the app for production to the `dist` folder.

## 🚀 Deployment <a name = "deployment"></a>

We automatically build and deploy the latest version to NPM.

## ✍️ Authors <a name = "authors"></a>

- [Adriaan Knapen](https://aknapen.nl) [![Addono@Gitlab](https://img.shields.io/badge/Gitlab-@Addono-orange?style=for-the-badge&logo=gitlab)](https://gitlab.com/Addono) [![Addono@Github](https://img.shields.io/badge/Github-@Addono-black?style=for-the-badge&logo=github)](https://github.com/Addono)