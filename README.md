# react-component-preview README

This is the README for your extension "react-component-preview". After writing up a brief description, we recommend including the following sections.

### 6/22/2020
Got caught up on the anatomy of a VS Code extension. 
Reading material: https://code.visualstudio.com/api/get-started/extension-anatomy

The Hello World extension does 3 things:

* Registers the onCommand Activation Event: `onCommand:extension.helloWorld`, so the extension becomes activated when user runs the Hello World command.
  * The demo helloWorld command is executed when the user opens up the command palette and types in the name of the extension, `Hello World`.
* Uses the contributes.commands Contribution Point to make the command Hello World available in the Command Palette, and bind it to a command ID extension.helloWorld.
* Uses the commands.registerCommand VS Code API to bind a function to the registered command ID extension.helloWorld.
