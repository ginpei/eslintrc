# `@ginpei/eslintrc`

## Install

```console
$ npm i -D @ginpei/eslintrc
$ npm i -D @typescript-eslint/eslint-plugin eslint eslint-config-prettier eslint-plugin-import eslint-plugin-prettier prettier
```

## Usage

- `.eslintrc.js`

```js
module.exports = {
  extends: "./node_modules/@ginpei/eslintrc/.eslintrc.js",
  rules: {
    // your rules here
  },
};
```

```console
$ npx eslint .
```
