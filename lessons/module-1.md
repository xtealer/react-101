# Module 1

Here we will install some programs, set the initial configuration, and get ready our development enviroment.


## Installation of the following tools:

- git: https://github.com/git-guides/install-git
- nodejs: https://nodejs.org/en/
- visual studio code (vscode): https://code.visualstudio.com/
- yarn: https://yarnpkg.com/lang/en/docs/install/


## Extensions for VSCODE

- GitLens: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
- ESLint: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
- SASS: https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented
- Material Icons: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
- Better Comments: https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments
- Prettier: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode


## Configuration for VSCODE

This must be set after the installation of all extensions shown in the last section, you may find instruction on how to do this [here](https://code.visualstudio.com/docs/getstarted/settings).

```
{
"editor.suggestSelection": "first",
"workbench.iconTheme": "material-icon-theme",
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.insertSpaces": false,
"editor.tabSize": 2,
"[sass]": {
  "editor.defaultFormatter": "syler.sass-indented"
},
"explorer.confirmDragAndDrop": false,
"git.confirmSync": false,
"typescript.updateImportsOnFileMove.enabled": "always",
"code-runner.runInTerminal": true,
"javascript.updateImportsOnFileMove.enabled": "always",
"diffEditor.ignoreTrimWhitespace": false,
"editor.formatOnSave": true
}
```

[Next Module](https://github.com/xtealer/react-101/blob/main/lessons/module-2.md)
