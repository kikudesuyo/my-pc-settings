# Visual Studio Code

## Extensions

```bash
cd my-pc-settings
cat vscode/extensions.txt | xargs -n 1 code --install-extension
```

## Keybindings

1. Visual Studio Code で `Preferences: Open Keyboard Shortcuts (JSON)` を開く
1. `vscode/keybindings.json` の内容をコピーする
1. 開いた `keybindings.json` に貼り付けて保存する

## Export

```bash
code --list-extensions > vscode/extensions.txt
```

<!-- LAST_UPDATED -->
最終更新: 2026-06-16 05:07 JST
<!-- /LAST_UPDATED -->
