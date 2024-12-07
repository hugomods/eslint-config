# HugoMods ESLint Config

[![License](https://flat.badgen.net/github/license/hugomods/eslint-config)](https://github.com/hugomods/eslint-config/blob/main/LICENSE)
[![Version](https://flat.badgen.net/npm/v/@hugomods/eslint-config)](https://www.npmjs.com/package/@hugomods/eslint-config)
[![Downloads](https://flat.badgen.net/npm/dt/@hugomods/eslint-config)](https://www.npmjs.com/package/@hugomods/eslint-config)

## Installation

```sh
npm i -D @hugomods/eslint-config
```

## Configuration

```js
// eslint.config.mjs
import config from '@hugomods/eslint-config';

export default config;
```

## Scripts

```json
{
  "scripts": {
    "lint:eslint": "eslint .",
    "lint:eslint:fix": "eslint . --fix"
  }
}
```
