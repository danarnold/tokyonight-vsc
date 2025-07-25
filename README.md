# Tokyo Night Bright

A Visual Studio Code color theme inspired by [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) and enkia's [tokyo-night/tokyo-night-vscode-theme](https://github.com/tokyo-night/tokyo-night-vscode-theme). The goal was to use the brighter palette of tokyonight.nvim to create a higher contrast theme, since I've found that enkia's version is too dark for my preferences. The result is a theme that's similar to tokyo-night-vscode but noticeably brighter.

## Screenshot

![A screenshot of VS Code editing the rails source code with the Tokyo Night Bright color scheme](assets/screenshot.png)

The above screenshot is using [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), [Material Product Icons](https://github.com/material-extensions/vscode-material-product-icons), and the [Material Icon Theme](https://github.com/material-extensions/vscode-material-icon-theme).

## Credits

- [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) for the color palette
- [tokyo-night/tokyo-night-vscode-theme](https://github.com/tokyo-night/tokyo-night-vscode-theme) for the original theme and highlighting rules
- [primer/github-vscode-theme](https://github.com/primer/github-vscode-theme) for highlighting rules

## Building

1. Clone this repository.
2. Run `npx vsce package` to create a VSIX file.
3. Install the VSIX in VS Code: `code --install-extension <your-vsix-file>`

## License

MIT
