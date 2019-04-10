### TSLint Configuration Web Computing

## Installation

```
npm i tslint-config-webcomputing --save-dev
```

## Usage
Add the following config in your `tslint.json` file, to extend from our basic configuration:
```
{
  "extends": "@webcomputing/tslint-config-webcomputing"
}
```
For angular workspaces, we recommend to extend from `tslint-angular.json`file
```
{
  "extends": "@webcomputing/tslint-config-webcomputing/tslint-angular"
}
```

## Visual Studio Code

The popular VSCode linting extension [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint) isn't able to support rules that need typing, e.g. `no-floating-promises` or `use-strict-boolean` and is hence deprecated.

Please make sure you use the new extension [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin) along with [tslint-language-service](https://github.com/angelozerr/tslint-language-service).
