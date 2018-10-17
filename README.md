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

https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf
