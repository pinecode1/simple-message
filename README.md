# simple-message
SNSのようなメッセージをユーザーごとに送信できるアプリケーション


# NewRead
MySQLとPHPを使ったSNSのような簡易Webアプリケーション

※開発中


# simple-message DB設計

## usersテーブル
|Column|Type|Options|
|------|----|-------|
|name|string|null: false|
|email|string|null: false|
|password|string|null: false|
### Association


## commentsテーブル
|Column|Type|Options|
|------|----|-------|
|text|text|
|user_id|integer|null: false, foreign_key: true|

### Association


