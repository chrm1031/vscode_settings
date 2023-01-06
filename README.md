# vscode_settings
VSCodeの設定やメモ用リポジトリ

## キーボードショートカットの変更・確認方法

### GUIで修正する場合
1. ```Ctrl + K, Ctrl + S```でキーボードショートカットを開く

### 直接ファイルを修正する場合
1. コマンドパレットを開く
```Ctrl + Shift + p```

2. ```keybindings.json``` と入力

3. キーバインドを設定する
```keybindings.json
[
  // 前のエディターにフォーカス
  {
    "key": "ctrl+shift+tab",
    "command": "workbench.action.previousEditor"
  },
  {
    "key": "ctrl+pageup",
    "command": "-workbench.action.previousEditor"
  },
  // 次のエディターにフォーカス
  {
    "key": "ctrl+tab",
    "command": "workbench.action.nextEditor"
  },
  {
    "key": "ctrl+pagedown",
    "command": "-workbench.action.nextEditor"
  },
  // 前のエディターグループへフォーカス
  {
    "key": "ctrl+pageup",
    "command": "workbench.action.focusPreviousGroup"
  },
  // 次のエディターグループへフォーカス
  {
    "key": "ctrl+pagedown",
    "command": "workbench.action.focusNextGroup"
  }
]
```

## よく使うコマンド & 覚えたいコマンド
| キー | 動作 |
| - | - |
| Ctrl + H | 置換 |
| Ctrl + Alt + Enter | 全て置換 |
| Ctrl + Home | ファイルの先頭に移動 |
| Ctrl + End | ファイルの末尾に移動 |
| Ctrl + Down | 行を下へスクロール |
| Alt + PageUp | 画面を上にスクロール |
| Alt + PageDown | 画面を下にスクロール |
| Ctrl + Tab | 次のタブへ移動 |
| Ctrl + Shift + Tab | 前のタブへ移動 |
| Alt + Left | 前に戻る |
| Alt + Right | 次に進む |
| Ctrl + \ | エディターを分割 |
| Ctrl + 1 | 左のエディターへフォーカス |
| Ctrl + 2 | サイドエディターへフォーカス |
| Ctrl + 3 | 右のエディターへフォーカス |
| Ctrl + Alt + Left | 左のエディターへタブを移動 |
| Ctrl + Alt + Right | 右のエディターへタブを移動 |