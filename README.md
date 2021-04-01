# tpu-lel_pages

- 東京工芸大学工学部 学習工学研究室のホームページファイルです．
- 編集直後にホームページに反映されるようになっていますので，慎重に取り扱って下さい．

# 編集方法

- /content/\*: ここ以下にあるファイルをそのままブラウザ上で書き換えれば上手くいきます．
  - 反映まで時間が掛かることがあります．
- /config.toml: メニューの一覧など，細かい調整はだいたいこのファイルを書き換えればできます．

## ローカル環境でのビルド

### hugo をインストール

macOS

```shell
$ brew install hugo
```

その他 OS などはこちらを参照
[https://gohugo.io/getting-started/installing](https://gohugo.io/getting-started/installing)

## サーバを実行

```shell
$ hugo server -D
```

`Web server is available at http://localhost:1313/ (bind address ..)`が出れば成功

ブラウザで[http://localhost:1313/](http://localhost:1313/)を開く
