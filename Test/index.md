# テスト

記述ルールは以下になります。

```
大項目(画面名) : ## 大項目（画面名）
中項目(機能名) : ### 中項目（機能名）
テスト内容:       - テスト内容
確認内容 :         - [ ] 確認内容
```

## ログイン画面

### ログイン機能
- 正しいメールアドレスとパスワードを入力してログインボタンをタップする
  - [ ] ホーム画面に遷移する
- 間違ったメールアドレスとパスワードを入力してログインボタンをタップする
  - [ ] エラーメッセージを表示する
  
## ユーザー一覧画面

### ユーザー招待機能
- 正しいメールアドレスを入力して招待ボタンをタップする(参考: [Github](https://github.com/))
  - [ ] メールアドレス入力後に非同期でユーザーを検索してアイコンを表示する
  - [ ] 検索結果のユーザーに招待メールを送る
