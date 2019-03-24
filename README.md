# vscode-theme-generator-quick-start

>Based almost entirely on [Tyriar's repo](https://github.com/Tyriar/vscode-theme-generator-quick-start).
>Updated to include *many* more color choices and a few options.

## Usage

**Clone and run for a quick way to get started with [vscode-theme-generator](https://github.com/skeptycal/vscode-theme-generator).**

## How to build the theme

You need [NodeJS](https://nodejs.org/en/) installed to run the generator.

```BASH
npm install
```

Make your changes to the colors in `index.ts` and hit `F5` to build the theme and launch the a new VS Code window with your theme available in the command palette (`ctrl`/`cmd+shift+p` > "Color Theme").

## Issues

- dark backgrounds can cause text to appear 'invisible' since the default black text doesn't seem to be replaced consistently by the foreground color chosen in the `index.ts` file

## Publishing

When you're ready to publish your theme just fill out the `"name"`, `"displayName", `"publisher"` and `"description"` values in the package.json and [publish it like any other extension](https://code.visualstudio.com/docs/extensions/publish-extension).
