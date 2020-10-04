# README

docker-composeによるRuby + MySQLのプレーンな開発環境です。

APIモードで動作します。

## バージョン
- Ruby
  - 2.7.2
- Rails
  - 6.0.3
- MySQL
  - 8.0.21

## 使い方
```
$ docker-compose up -d
$ docker-compose run --rm web rails db:create
```
