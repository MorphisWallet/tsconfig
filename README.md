# tsconfig [![NPM version](https://img.shields.io/npm/v/@morphis-labs/tsconfig.svg)](https://www.npmjs.com/package/@morphis-labs/tsconfig)

> Public [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html) by Morphis Labs

## Install

```sh
npm install --save-dev @morphis-labs/tsconfig
yarn add -D @morphis-labs/tsconfig
pnpm add -D @morphis-labs/tsconfig
```

_This config requires TypeScript 4.7 or later._

## Usage

`tsconfig.json`

```json
{
  "extends": "@morphis-labs/tsconfig",
  "compilerOptions": {
    "outDir": "custom_dir_you_want"
  },
  "include": ["custom/directory/you/want"]
}
```

When you are targeting a higher version of Node.js, check the relevant ECMAScript version and add it as `target`:

```json
{
  "extends": "@morphis-labs/tsconfig",
  "compilerOptions": {
    "outDir": "dist",
    "target": "ES2021"
  }
}
```
