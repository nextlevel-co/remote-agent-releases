# remote-agent releases

NL Remote の Agent（操作される Mac に入れるアプリ）の、公証済みのビルドを配るリポジトリです。ソースコードは置いていません。

アプリには接続先を組み込んでいません。登録のときに、接続先のホスト名と、管理者が発行した登録コードを入力します。

## インストール

```bash
brew tap nextlevel-co/tap
brew install --cask remote-agent
```

## 更新

```bash
brew upgrade --cask remote-agent
```

動作環境：macOS 14 以上、Apple シリコン
