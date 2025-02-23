# `@sharegate/typescript-config`

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](../../LICENSE.md)
[![npm version](https://img.shields.io/npm/v/@sharegate/typescript-config)](https://www.npmjs.com/package/@sharegate/typescript-config)

This packages provides a base TypeScript configuration depending on the JavaScript runtime environment which you intend to run your code in. 
These are tsconfig.json files which your project extends from which simplifies your tsconfig.json by handling the runtime support.

## Installation

Install the package.

**With npm**
```shell
npm i --save-dev @sharegate/typescript-config
```

**With yarn**
```shell
yarn add --dev @sharegate/typescript-config
```

## Usage

### Create React App Project

To start, create a tsconfig.json in the root of your project.

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@sharegate/typescript-config/cra.json",
  "compilerOptions": {
    "baseUrl": ".",
  },
  "include": ["src"],
  "exclude": ["node_modules"]
}
```

### NextJS Project

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@sharegate/typescript-config/nextjs.json",
  "compilerOptions": {
    "baseUrl": ".",
  },
  "include": ["src"],
  "exclude": ["node_modules"]
}
```

### React Library Project

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@sharegate/typescript-config/react-library.json",
  "compilerOptions": {
    "baseUrl": ".",
  },
  "include": ["src"],
  "exclude": ["node_modules"]
}
```

### Other type of React Project

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@sharegate/typescript-config/react.json",
  "compilerOptions": {
    "baseUrl": ".",
  }
}
```

### TypeScript Library

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@sharegate/typescript-config/library.json",
  "compilerOptions": {
  }
}
```

### All Other TypeScript Projects

```json
{
  "$schema": "https://json.schemastore.org/tsconfig",
  "extends": "@sharegate/typescript-config/base.json",
  "compilerOptions": {
  }
}
```

## License

Copyright © 2023, GSoft inc. This code is licensed under the Apache License, Version 2.0. You may obtain a copy of this license at https://github.com/workleap/gsoft-license/blob/master/LICENSE.