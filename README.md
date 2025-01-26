# Cursor ドキュメント

このリポジトリには[Cursorのドキュメント](https://docs.cursor.com) のソースコードが含まれています。

有用な変更を提案する場合は、プルリクエストを開いてください！

### 開発

ドキュメントの変更をローカルでプレビューするには、[Mintlify CLI](https://www.npmjs.com/package/mintlify) をインストールしてください。インストールするには、以下のコマンドを使用します：

```
npm i -g mintlify
```

ドキュメントのルートディレクトリ（`mint.json`があるディレクトリ）で以下のコマンドを実行します：

```
mintlify dev
```

#### Troubleshooting

- Mintlify devが実行されていない - `mintlify install`を実行して依存関係を再インストールしてください。
- ページが404エラーとして表示される - `mint.json`があるディレクトリで実行していることを確認してください。
