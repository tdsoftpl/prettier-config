# [@tdsoft/prettier-config](https://www.npmjs.com/package/@tdsoft/prettier-config)

## @tdsoft config

| printWidth | trailingComma | tabWidth | semi | singleQuote | bracketSpacing | bracketSameLine | arrowParens | endOfLine | jsxSingleQuote | proseWrap | quoteProps | useTabs | htmlWhitespaceSensitivity |
| ---------- | ------------- | -------- | ---- | ----------- | -------------- | --------------- | ----------- | --------- | -------------- | --------- | ---------- | ------- | ------------------------- |
| 100        | none          | 4        | true | false       | false          | false           | always      | auto      | false          | preserve  | as-needed  | false   | css                       |

## How to use this config

### Reference it within `package.json` file:
```json
{
  "name": "@tdsoft/project-name",
  "description": "Project description.",
  ...
  "prettier": "@tdsoft/prettier-config"
}
```

### Create a `.prettierrc`, `.prettierrc.yaml`, `.prettierrc.yml`, `.prettierrc.json` or `.prettierrc.json5` file and export a string:
```json
"@tdsoft/prettier-config"
```

## How to override
Import the `@tdsoft/prettier-config` file in a `.prettierrc.js`, `.prettierrc.cjs`, `prettier.config.js`, or `prettier.config.cjs` file and override desired properties.
```js
module.exports = {
  ...require("@tdsoft/prettier-config"),
  semi: false
};
```
