# eslint-config-lalilo

## Install

```
yarn add -eslint-config-lalilo

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

```

## Usage


```ts
//eslint.js

module.exports = {
  root: true,
  extends: "lalilo",
  plugins: "@typescript-eslint",
  parser: '@typescript-eslint/parser',
  parserOptions: {
    project: './tsconfig.json',
    tsconfigRootDir: __dirname,
  },
}
```

You will probably need to change your `.eslintrc` in a `.eslintrc.js`
