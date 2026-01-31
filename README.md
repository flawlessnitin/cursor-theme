# My Custom Theme

A beautiful custom color theme for Visual Studio Code.

## Setup

### Installation

1. **Clone the repository**

   ```Shell
   git clone https://github.com/flawlessnitin/cursor-theme.git
   ```

2. **Copy to VS Code extensions directory**

   Navigate to your VS Code extensions folder and copy the cloned folder there:

   * **Windows:** `%USERPROFILE%\.vscode\extensions\`
   * **macOS/Linux:** `~/.vscode/extensions/`

   Example:

   ```Shell
   # Windows
   xcopy cursor-theme %USERPROFILE%\.vscode\extensions\cursor-theme\ /E /I

   # macOS/Linux
   cp -r cursor-theme ~/.vscode/extensions/
   ```

3. **Restart VS Code**

   Close and reopen Visual Studio Code to load the extension.

### Testing During Development

If you want to test changes while developing the theme:

1. Open this folder in VS Code
2. Press `F5` to launch an Extension Development Host window
3. The theme will be automatically loaded in the new window
4. Go to `File > Preferences > Color Theme` and select "My Custom Theme"

## Usage

Once installed, activate the theme:

1. Open Command Palette (`Ctrl+Shift+P` on Windows/Linux or `Cmd+Shift+P` on macOS)
2. Type "Color Theme" and select **Preferences: Color Theme**
3. Choose **My Custom Theme** from the list

Alternatively:

* Go to `File > Preferences > Color Theme` (or `Code > Preferences > Color Theme` on macOS)
* Select **My Custom Theme**

## Customization

You can customize the theme colors and syntax highlighting by editing `themes/my-custom-theme-color-theme.json`:

* **colors**: Controls UI elements (sidebar, status bar, editor background, panels, etc.)
* **tokenColors**: Controls syntax highlighting for different code elements

After making changes, reload VS Code or press `F5` in the development window to see updates.

### Useful Resources

* [VS Code Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)
* [TextMate Scopes](https://www.sublimetext.com/docs/scope_naming.html)
* [VS Code Theme Guide](https://code.visualstudio.com/api/extension-guides/color-theme)

## License

MIT
