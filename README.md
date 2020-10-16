# eslint-config-lalilo

## Install

```
yarn add -eslint-config-lalilo

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
