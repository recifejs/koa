<img alt="RecifeJs" width="400" src="https://raw.githubusercontent.com/recifejs/recife/master/logo.png" />

[![npm version](https://img.shields.io/npm/v/recife-koa?style=flat-square&logo=npm)](https://www.npmjs.com/package/recife-koa) [![License: MIT](https://img.shields.io/github/license/recifejs/recife-koa?style=flat-square)](https://github.com/recifejs/recife-koa/blob/master/LICENSE) [![Node.js CI](https://img.shields.io/github/workflow/status/recifejs/recife-koa/Node.js%20CI?style=flat-square&logo=github)](https://github.com/recifejs/recife-koa/workflows/Node.js%20CI)

Recife Koa is a integration of recifejs with [koa](https://koajs.com/). For more details access the [documentation](https://recifejs.org/).

## Install

```bash
npm install recife-koa
# or
yarn add recife-koa
```

## Using in RecifeJs project

Open file `config/app.ts` and insert the value `koa` in the property `httpFramework`:

```ts
import { AppConfig } from 'recife';

export const config: AppConfig = {
  // ...
  httpFramework: 'koa'
  // ...
};
```

## License

Recife Koa is open source software [licensed as MIT](https://github.com/recifejs/recife-koa/blob/master/LICENSE).
