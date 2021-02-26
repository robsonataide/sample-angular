# Front-end configuration

## 1 - Install node.js (npm included) LTS version 64-bit (LTS - Long Term Support provides better stability)

https://nodejs.org/en/download/

## 2 - Check installation (versions)

```console
foo@bar:~$ node -v
v10.19.0
```

```console
foo@bar:~$ npm -v
6.14.4
```

> Note: Expected Output (version should be similar or higher that the example)

## 3 - Install Visual Studio Code

https://code.visualstudio.com/

## 4 - Extensions used for Visual Studio Code

### Required

esbenp.prettier-vscode  
msjsdiag.debugger-for-chrome  
streetsidesoftware.code-spell-checker

### Optional

dbaeumer.vscode-eslint  
eamodio.gitlens  
42Crunch.vscode-openapi  
ms-azuretools.vscode-docker  
redhat.vscode-yaml  
fabiospampinato.vscode-todo-plus  
humao.rest-client  
PKief.material-icon-theme

> Note: First part name of the provider, second part name of the extension, search for the extension in vscode  
> For example:  
> provider --> esbenp  
> extension --> prettier-vscode

## 5 - List the current installed extensions:

```console
foo@bar:~$ code --list-extensions
```

https://stackoverflow.com/questions/35773299/how-can-you-export-the-visual-studio-code-extension-list
