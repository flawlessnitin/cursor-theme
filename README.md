# My Custom Theme

A beautiful custom color theme for Visual Studio Code.

## Installation

### From Source

1. Clone or download this repository
2. Copy the folder to your VS Code extensions directory:
   * **Windows:** `%USERPROFILE%\.vscode\extensions`
   * **macOS/Linux:** `~/.vscode/extensions`
3. Restart VS Code
4. Go to `File > Preferences > Color Theme` and select "My Custom Theme"

### For Development

1. Open this folder in VS Code
2. Press `F5` to open a new window with the extension loaded
3. Go to `File > Preferences > Color Theme` and select "My Custom Theme"

## Customization

You can customize the theme by editing the `themes/my-custom-theme-color-theme.json` file:

* **colors**: UI elements (sidebar, status bar, editor background, etc.)
* **tokenColors**: Syntax highlighting for code

### Useful Resources

* [VS Code Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)
* [TextMate Scopes](https://www.sublimetext.com/docs/scope_naming.html)
* [VS Code Theme Guide](https://code.visualstudio.com/api/extension-guides/color-theme)

## Publishing

To publish your theme to the marketplace:

```Shell
# Install vsce (VS Code Extension Manager)
npm install -g @vscode/vsce

# Package your extension
vsce package

# Publish (requires a publisher account)
vsce publish
```

## License

MIT
