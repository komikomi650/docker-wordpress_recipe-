# docker-wordpress_recipe-

# 検証用 Docker版(コンテナ版) Wordpress (MySQL)

外部公開前に投稿内容の不備確認や表示内容の不備・検証用として
作成しました。

構成として、Wordpress（最新版) MySQL v8.0を使用するように設定しています。

## 使用方法
前提として ***コマンド：docker-compose*** が使用できる環境が必要です。

1. git cloneにて **ymlファイルを取得**
   
   `git clone https://github.com/komikomi650/docker-wordpress_recipe-.git`

2. docker-composeを使用してbuild

   ※イメージのダウンロードがされるので、ネットワーク環境に注意

   `docker-compose build`

3. docker-composeでコンテナ稼働
   
     `docker-compose up`


## ブラウザを使用して下記URLを入力

`http://127.0.0.1:8088`

DBのID・PASSWORDは `WORDPRESS` にしています。
必要に応じて更新してください。

