# [@tdsoft/prettier-config](https://www.npmjs.com/package/@tdsoft/prettier-config)

## @tdsoft config

| printWidth | trailingComma | tabWidth | semi | singleQuote | bracketSpacing | jsxBracketSameLine | arrowParens | endOfLine | jsxSingleQuote | proseWrap | quoteProps | useTabs | htmlWhitespaceSensitivity |
| ---------- | ------------- | -------- | ---- | ----------- | -------------- | ------------------ | ----------- | --------- | -------------- | --------- | ---------- | ------- | ------------------------- |
| 100        | none          | 4        | true | false       | false          | false              | always      | auto      | false          | preserve  | as-needed  | false   | css                       |

## How to use this config

### Reference it within `package.json` file:
```
{
  "prettier": "@tdsoft/prettier-config"
}
```

### Export a string from `.prettierrc.json` file:
```
{
  "@tdsoft/prettier-config"
}
```

## How to override
Import the file in a `.prettierrc.js`, and override desired properties.
```
module.exports = {
  ...require("@tdsoft/prettier-config"),
  semi: false
};
```