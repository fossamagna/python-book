# ゼロから学ぶ Python

このリポジトリはオンライン学習サイト[ゼロから学ぶ Python]のソースコードリポジトリです。

## 必要なもの

ソースコードから HTML ページを生成するには下記のものが必要です。

- Python
- pipenv
- make

## ビルド

HTML を生成するには下記のコマンドを実行してください。

```shell
$ make init
$ make build
```

ビルド結果をブラウザ上で確認するには次のコマンドを実行します。

```shell
$ make serve
```

http://localhost:8000 にアクセスすると Web ページが表示されます。

[ゼロから学ぶ Python]: https://rinatz.github.io/python-book
