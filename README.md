# pf snippets

Followed this guide to create the extension:
https://blog.lftechnology.com/build-your-own-vs-code-snippet-extension-e8faa76eb9c6

## What's in the folder

* This folder contains all of the files necessary for your extension.
* `package.json` - this is the manifest file that defines the location of the snippet file and specifies the language of the snippets.
* `snippets/react.json` - the file containing all react snippets.
* `snippets/core.json` - the file containing all core snippets.

## Get up and running straight away

* Press `F5` to open a new window with your extension loaded.
* Create a new file with a file name suffix matching your language.
* Verify that your snippets are proposed on intellisense.

## Make changes

* You can relaunch the extension from the debug toolbar after making changes to the files listed above.
* You can also reload (`Ctrl+R` or `Cmd+R` on Mac) the VS Code window with your extension to load your changes.

## Install your extension

* To start using your extension with Visual Studio Code copy it into the `<user home>/.vscode/extensions` folder and restart Code.
* To share your extension with the world, read on https://code.visualstudio.com/docs about publishing an extension.
