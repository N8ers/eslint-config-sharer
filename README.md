# eslint-config-sharer

## Using a shared config

1. Setup `eslint` if you have not already via `npm init @eslint/config`. We prefer `eslint.js` files over `eslint.json` files.
1. Install the `eslint-config-sharer` package from npm [eslint-config-sharer](https://www.npmjs.com/package/eslint-config-sharer).
1. Extend your `.eslint.js` with either `base` or `base2`, or both! Just remember order matters.

```js
// .eslintrc.js

module.exports = {
  env: {},
  extends: ["sharer/base", "sharer/base2"],
  overrides: [],
  parserOptions: {},
  rules: {},
}
```
