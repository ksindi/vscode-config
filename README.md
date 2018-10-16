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

Using atom keybindings extension

| Action           | Shortcut     | Source        |
| ---------------- | ------------ | ------------- |
| Find text        | ctrl+shift+f | atom          |
| Copy line down   | ctrl+shift+d | atom          |
| Move line up     | ctrl+up      | atom          |
| Move line down   | ctrl+down    | atom          |
| Uppercase        | ctrl+k+u     | atom          |
| Lowercase        | ctrl+k+l     | atom          |
| Preview markdown | ctrl+shift+m | atom          |

https://github.com/nwinkler/atom-keyboard-shortcuts
