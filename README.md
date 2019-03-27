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
