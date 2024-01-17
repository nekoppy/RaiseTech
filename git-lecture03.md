# 第3回課題

## 課題
1. APサーバーについて

- APサーバーの名前：PUMA
- APサーバーのバージョン：５.６.７
- サーバー起動（下）
<img width="1299" alt="スクリーンショット 2024-01-10 15 50 31" src="https://github.com/nekoppy/RaiseTech/assets/53550588/ec217dc9-a2c5-434c-b755-a9aa460cf161">
- サーバー終了し、再起動0K（control+Cで終了し、rails sで再起動）

2. DBサーバーについて調べる

- サンプルアプリケーションで使ったDBエンジン：MySQL
- Cloud9で動作しているバージョン：8.0.35
- DBサーバーを終了させ、引き続きアクセス可能か？について。
  ＝＞sudo service mysqld stopで停止し、sudo service mysqld startで起動OK。
- Railsの構成管理ツールの名前：Bundler

## 学び

* DBのセットアップ、使い方
* 動作環境の確認方法、指定の環境に合わせることの重要性

## 感想

- 最初の段階でCloud9のプラットホームをAmazonLinux2023で作ってしまい、DBがセットアップできずに躓いた。構築環境によって手順が大きく違うことに驚いた。
