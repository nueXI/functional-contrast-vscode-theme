# Welcome to your VS Code Extension

## What's in the folder

* This folder contains all of the files necessary for your color theme extension.
* `package.json` - this is the manifest file that defines the location of the theme file and specifies the base theme of the theme.
* `themes/Functional Contrast-color-theme.json` - the color theme definition file.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Open `File > Preferences > Color Themes` and pick your color theme.
* Open a file that has a language associated. The languages' configured grammar will tokenize the text and assign 'scopes' to the tokens. To examine these scopes, invoke the `Developer: Inspect Editor Tokens and Scopes` command from the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac) .

## Make changes

* Changes to the theme file are automatically applied to the Extension Development Host window.

## Adopt your theme to Visual Studio Code

* The token colorization is done based on standard TextMate themes. Colors are matched against one or more scopes.

To learn more about scopes and how they're used, check out the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Build your extension

* This project has no local `devDependencies`, so package via `npx`: `npx @vscode/vsce package`.
* This reads `package.json` and bundles everything not excluded by `.vscodeignore` into a `.vsix` file (e.g. `functional-contrast-custom-1.0.0.vsix`).
* Bump the `version` field in `package.json` first if you don't want to overwrite the existing `.vsix`.

## Install your extension

* From the packaged `.vsix`: run `code --install-extension functional-contrast-custom-1.0.0.vsix`, or in VS Code open the Extensions view `...` menu and choose `Install from VSIX...`.
* Alternatively, copy the extension folder into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.
