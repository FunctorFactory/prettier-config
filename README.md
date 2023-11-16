<!-- Title -->
<h1 align="center">
  prettier-config
</h1>

<!-- Description -->
<h4 align="center"> 
  The <a href="https://prettier.io/docs/en/configuration.html#sharing-configurations">shareable configuration</a>
  for <a href="https://prettier.io/">Prettier</a> used in all Functor Factory projects
</h4>

<!-- Badges -->
<p align="center">
  <a href="https://www.npmjs.com/package/@functorfactory/prettier-config">
    <img
      src="https://img.shields.io/npm/v/@functorfactory/prettier-config?style=flat-square"
      alt="Package Version"
    />
  </a>

  <a href="https://github.com/FunctorFactory/prettier-config/actions?query=branch%3Amain+workflow%3ARelease">
    <img
       src="https://img.shields.io/github/actions/workflow/status/functorfactory/prettier-config/release.yml?branch=main?style=flat-square"
      alt="Build Status"
    />
  </a>
</p>

<!-- Quicklinks -->
<p align="center">
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#license">License</a>
</p>

<br>

## Installation

```sh
npm install -D @functorfactory/prettier-config prettier
```

or

```sh
yarn add -D @functorfactory/prettier-config prettier
```

or

```sh
pnpm add -D @functorfactory/prettier-config prettier
```

## Usage

To use this configuration, add a `prettier` field to your `package.json`

```json
{
  ...
  "prettier": "@functorfactory/prettier-config"
  ...
}
```

## License

GPL-3.0 Or Later
