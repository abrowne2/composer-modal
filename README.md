# Composer Modal

Opens Cursor chat in a new window with a single command, reducing the steps needed to start a focused conversation.

## Features

- **Quick Access**: Launch Cursor chat in a dedicated window instantly
- **Keyboard Shortcut**: Default binding to `Cmd+Shift+M` (Mac) or `Ctrl+Shift+M` (Windows/Linux)
- **Clean Workflow**: Keeps your main editor uncluttered while chatting

## Usage

### Command Palette
1. Open Command Palette (`Cmd/Ctrl+Shift+P`)
2. Type "Open Cursor Chat in New Window"
3. Press Enter

### Keyboard Shortcut
Press `Cmd+Shift+M` (Mac) or `Ctrl+Shift+M` (Windows/Linux) while in the editor

## Installation

### From Source
1. Clone this repository
2. Run `npm install`
3. Run `npm run compile`
4. Press `F5` to launch a new VSCode window with the extension loaded

### From VSIX
1. Build the extension: `vsce package`
2. Install: `code --install-extension composer-modal-*.vsix`

## Requirements

- VSCode 1.74.0 or higher
- Cursor IDE (for the chat functionality)

## Extension Settings

This extension contributes the following:

* Command: `composer-modal.openChatInNewWindow`
* Default Keybinding: `Cmd+Shift+M` (Mac) / `Ctrl+Shift+M` (Windows/Linux)

## Development

```bash
# Install dependencies
npm install

# Compile TypeScript
npm run compile

# Watch for changes
npm run watch
```

## License

See [LICENSE](LICENSE) file for details.
