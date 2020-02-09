# 概要

外部から MySQL を操作するデモ用リポジトリ

## 使い方

```bash
# デモ用の MySQL プロジェクトのディレクトリに移動
cd mysql_for_demo

# デモ用の MySQL Docker コンテナを起動
docker-compose up -d

# 外部から MySQL を操作するプロジェクトのディレクトリに移動
cd operate_mysql_from_external

# 外部から mysqldump する Docker コンテナを一時的に実行 
docker-compose run --rm mysqldump
```

## mysqldump の出力先

`operate_mysql_from_external/mysqldump/dumpfiles`

## MySQL の初期データ

`mysql_for_demo/mysql/mysql_init/inital.sql`