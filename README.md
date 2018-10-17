# vscode-config

## Exporting extensions

```bash
code --list-extensions | xargs -L 1 echo code --install-extension > extensions.list
```

## Installing extensions

```bash
cat extensions.list | bash
```

## Useful shortcuts

| Action            | Shortcut             |
| ----------------- | -------------------- |
| Show explorer     | Ctrl+Shift+E         |
| Go to file        | Ctrl+P               |
| Move line up/down | Alt+up/down          |
| Delete line       | Ctrl+K               |
| Find and replace  | Ctrl+Shift+H         |
| Uppercase         | Ctrl+Shift+P > Upper |
| Lowercase         | Ctrl+Shift+P > Lower |
| Preview markdown  | Ctrl+Shift+V         |


https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf
