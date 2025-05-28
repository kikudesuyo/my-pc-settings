### ファイルの概要

### Homebrew 経由でのアプリ一覧:

- ファイル: Brewfile
- インストール方法:

```bash
cd my-pc-settings
brew bundle
```

### vscode の拡張機能一覧

- ファイル: vscode-extensions.txt
- インポート手順:

```bash
cat vscode-extensions.txt | xargs -n 1 code --install-extension
```

### vscode のキーバインド設定

- ファイル: vscode-keybindings.json
- 手順:
  1. Preferences: Open Keyboard Shortcuts を開く
  1. keybindings.json を開き。ファイルの中身を差し替える。

### karabiner でのキーバインド設定

ファイル: karabiner.json
手順:

- ` ~/.config/karabiner/karabiner.json`のファイルを置き換えてください。

⚠️ 既存のキーバインド設定は上書きされます。必要に実行前にバックアップを取ってください。

```
cd my-pc-settings
cp karabiner.json ~/.config/karabiner/karabiner.json
```
