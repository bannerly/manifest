# bannerly manifest

[bannerly](https://github.com/bannerly) のリポジトリ群を [tsrc](https://your-tools.github.io/tsrc/) でまとめて取得・同期するためのマニフェストです。

## 使い方

```sh
pipx install tsrc

mkdir bannerly && cd bannerly
tsrc init https://github.com/bannerly/manifest.git
tsrc sync
```

## 含まれるリポジトリ

| dest | リポジトリ | 内容 |
|---|---|---|
| `server` | [bannerly/server](https://github.com/bannerly/server) | bannerly 広告配信サーバー |
| `sdk` | [bannerly/sdk](https://github.com/bannerly/sdk) | bannerly 用 Expo / React Native SDK（アクセス権が必要です） |
| `manifest` | [bannerly/manifest](https://github.com/bannerly/manifest) | このマニフェスト自体 |

定義は `manifest.yml` にあります。リポジトリを追加・変更する場合はこのファイルを編集してください。
