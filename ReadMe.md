# Claude Gruvbox

Claude Gruvbox is a light VS Code theme inspired by the soft, warm aesthetics of Claude.com and the familiar Gruvbox color palette.

## Highlights

- Warm off-white editor background
- Reusing the great muted Gruvbox-inspired color palette from https://github.com/Weevil-Breeder/sepia-for-vscode and https://plugins.jetbrains.com/plugin/16118-sepia-theme
- High readability for long coding sessions
- Clean, neutral light theme for everyday development

## Theme details

This extension contributes a single theme entry:

- Label: `Claude Gruvbox`
- File: `themes/claude-gruvbox-color-theme.json`

## Installation

### Option 1: Install from the local extension folder

1. Open this repository in VS Code.
2. Press `F5` to launch a new Extension Development Host window.
3. In the new window, open the Command Palette.
4. Choose `Preferences: Color Theme` and select `Claude Gruvbox`.

### Option 2: Package and install the extension

From the repository root:

```bash
npx @vscode/vsce package
```

Then install the generated `.vsix` file in VS Code:

```bash
code --install-extension claude-gruvbox-theme-*.vsix
```

## License

This project is provided as-is for personal and development use.
