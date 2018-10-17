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

| Action            | Shortcut             | Source |
| ----------------- | -------------------- | ------ |
| Show explorer     | Ctrl+Shift+E         |        |
| Go to file        | Ctrl+P               |        |
| Move line up/down | Ctrl+up/down         | Atom   |
| Delete line       | Ctrl+K               |        |
| Find and replace  | Ctrl+Shift+F         | Atom   |
| Save All          | Ctrl+Alt+S           |        |
| Uppercase         | Ctrl+Shift+P > Upper |        |
| Lowercase         | Ctrl+Shift+P > Lower |        |
| Preview markdown  | Ctrl+Shift+M         | Atom   |


https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf
