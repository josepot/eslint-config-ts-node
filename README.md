# eslint-config-ts-node

This package is just a subset of the [ESLint configuration](https://github.com/facebook/create-react-app/tree/master/packages/eslint-config-react-app) used by [Create React App](https://github.com/facebook/create-react-app), but keeping those rules that are relevant for [ts-node](https://github.com/TypeStrong/ts-node) projects.

## Usage

Install this package, ESLint and the necessary plugins.

```sh
npm install --save-dev eslint-config-ts-node @typescript-eslint/eslint-plugin@2.x @typescript-eslint/parser@2.x babel-eslint@10.x eslint@6.x eslint-plugin-import@2.x
```

Then create a file named `.eslintrc.json` with following contents in the root folder of your project:

```json
{
  "extends": "ts-node"
}
```
