# はじめに
このリポジトリは、Google Chromeの拡張をNext.jsで書くためのテンプレートリポジトリになります。

# 使い方

1. リポジトリをcloneする

```bash
git clone git@github.com:yushimatenjin/next-js-chrome-extension-starterkit.git
```

2. ライブラリをインストールする

```bash
yarn
```

3. Chrome Extensionを作成する

```bash
yarn export
```

4. Chrome Extensionを登録する

  a. `chrome://extensions/`にアクセス  
  b. 拡張機能をパッケージ化  
  c. extensionsディレクトリをアップロード  


# 開発について

- `Link`は可能ですが、`URL`の指定を`.html`まで記述する必要があります.
- アプリ名などを指定する場合には`dist/manifest.json`を書き換えます.