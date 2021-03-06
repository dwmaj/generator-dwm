# generator-bootstrap

> A DWMAJ generator to easily start a project

![stability-stable](https://img.shields.io/badge/stability-stable-green.svg?style=flat-square)
[![NPM version](https://img.shields.io/npm/v/@dwmaj/generator-bootstrap.svg?style=flat-square)](https://www.npmjs.com/package/@dwmaj/generator-bootstrap)
[![License](https://img.shields.io/badge/license-UNLICENSE-green.svg?style=flat-square)](https://github.com/dwmaj/generator-bootstrap/blob/master/UNLICENSE)
[![Build Status](https://img.shields.io/travis/com/dwmaj/generator-bootstrap.svg?style=flat-square)](https://travis-ci.com/dwmaj/generator-bootstrap)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=flat-square)](https://conventionalcommits.org)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release)

## Prerequisites

- Node (of course)
- Yeoman : `npm i -g yo`

## Installation

`npm i -g @dwmaj/generator-bootstrap`

## Usage

```bash
cd ~/heaj
yo @dwmaj/bootstrap
```

Then, answer to the few questions and follow the instructions.

> If you have an env variable `DWMAJ_GH_TOKEN` with a [personal token](https://github.com/settings/tokens),
> the generator will be able to create your repo and initialize git. Just accept…

---

## Emergency (via `npx`)

> You can not install globally. It can take several minutes… ⏳

`npx -p yo -p @dwmaj/generator-bootstrap -c 'yo @dwmaj/bootstrap'`

---

## Want to contribute?

[check this](./CONTRIBUTING.md)

---

## License

[UNLICENSE](./UNLICENSE) © [DWMAJ team](http://dwm.re/)
