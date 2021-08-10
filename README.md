# ts-node-dev-setup
My setup to develop in TypeScript for Node.js


## Contents
tbd

## Quick setup
Here are the steps how I setup my development environment for TypeScript.
1. Create a new git repository (for the purpose of this tutorial, we assume the name is `my-repo`)
1. Clone this repo somewhere else, omitting the history

```bash
git clone --depth=1 --branch=main https://github.com/henningkerstan/ts-node-dev-setup
```

1. copy all files from the repo except for the `.git` folder into your `my-repo` folder; afterwards you may remove the `ts-node-dev-setup` folder 

1. Now update the included (and incomplete!) `package.json` by running `npm init` in your new repo

1. Update the `.vscode/settings.json` and set `licenser.author` and `enocean-core` (if you plan to use the licenser extension for automatically adding a license notice in new files)

1. Install the necessary dev dependencies:
```bash
npm i --save-dev typescript @types/node typedoc jasmine @types/jasmine jasmine-ts jasmine-spec-reporter license-checker np husky prettier ts-node eslint eslint-config-prettier eslint-config-standard eslint-plugin-import eslint-plugin-prettier eslint-plugin-promise @typescript-eslint/eslint-plugin @typescript-eslint/parser
```


## Explanations
tbd