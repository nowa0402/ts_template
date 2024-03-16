# TypeScript Development Template for Backend

TypeScript Templateリポジトリ backend用

## 使用方法

テンプレート配置後、[package.json](./package.json)の以下項目編集

```json
{
  "name": "{プロジェクト名}",
  "version": "1.0.0",
  "description": "{プロジェクトの説明}",
  "main": "{必要に応じて編集}"
}

```

設定完了後`npm install`でパッケージをインストールする

## 仕様

◎ Node

node: 20.x

[volta](https://volta.sh/)でNodeのバージョンを固定。
使用しない場合は、[package.json](./package.json)から`volta`の項目を削除

◎ 初期パッケージ

- typescript
- ts-node: debug用パッケージ
- biome: フォーマッター・リンター
- jest: テストライブラリ

### VsCode

設定は[settings.json](./.vscode/settings.json)参照
拡張機能は[extensions.json](./.vscode/extensions.json)参照

### Formatter Linter

[Biome](https://biomejs.dev/)

設定は[biome.json](./biome.json)参照

### Test

[jest](https://jestjs.io/ja/)
