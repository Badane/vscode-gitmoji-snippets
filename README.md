# "gitmoji" snippets package for Visual Studio Code

## Forked from <a href="https://github.com/thierrymichel/vscode-gitmoji-snippets">VSCode Gitmoji snippets</a>

>This extension helps you to add emoji on your commit messages.
>Using emojis on commit messages provides an easy way of identifying the purpose or intention of a commit with only looking at the emojis used.

## Installation
### Solution 1
To install this extension, you must package it into a vsix file.
to do so, in the directory, run : 
`vsce package`
>if vsce command is not installed, you can install it with node
`npm install -g vsce`
This will produce a vsix file called something like vscode-gitmoji-snippets-0.0.1.vsix
Then use the `Install from vsix` under the `...`

### Solution 2
You can manually install your extension by placing the extension directory in 
`/home/your-username/.vscode/extensions/` (linux / MacOS)
`/Users/[your-username]/.vscode/extensions/)` (Windows)