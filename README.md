# 事前準備

Node.jsをインストールしておいてください。

- [Node\.js](https://nodejs.org/ja/)

## インストール

コマンドラインで次のコマンドを入力して必要なモジュールをインストールしてください。SASSなどのコンパイラーが入ります。

```
npm install
```

## コンパイル＆起動

作業するときは次のコマンドを入力ください。SASSは自動的にコンパイルされ、BrowserSyncでリアルタイムで編集結果がブラウザに表示されます。

```
npm run serve
```

## 最終成果物の作成

ウェブで公開するときは次のコマンドを入力します。`dist` フォルダーに公開用ファイルが一式用意されます。

```
npm run dist
```

## 補足

このリポジトリはGoogle Web Starter Kitをベースにカスタマイズしています。

- [Web Starter Kit  \|  Web  \|  Google Developers](https://developers.google.com/web/tools/starter-kit/?hl=ja)
