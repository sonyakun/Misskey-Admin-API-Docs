# Unoffical Misskey API Admin Endpoint List (Japanese)

※これはMisskey 13.14.2現在での情報を元に構成しているため、古くなっている可能性があります。

Misskeyサーバーの作成にはGitpod([Gitpod Misskey](https://gitlab.com/acefed/gitpod-misskey))を利用しています。
## 
abuse-user-reports
ユーザー報告の一覧表示に利用される。

meta
通常のmetaと同じ。多分。

update-meta
metaの内容を更新する。

show-users
総ユーザーの一覧を表示。

get-table-stats
DBの情報を表示する。
## invite
invite/create
招待コードを作成。

invite/list
招待コードの一覧を表示。

## roles
roles/list
ロールの一覧を表示。

roles/create
ロールを新規作成。

roles/users
ロールを付与されているユーザーを表示？

## emoji
emoji/list
絵文字一覧を表示。

emoji/add
絵文字を追加。

## federation
federation/instances
連合中のインスタンス(サーバー)を一覧表示?

## queue
queue/deliver-delayed
用途不明。ジョブキューメニュー選択時にリクエストの送信を確認。

queue/promote
全てのキューを今すぐ再試行する。

## drive
drive/files
全ユーザーのドライブのファイル一覧を表示する。

## announcements
announcements/list
お知らせの一覧。

announcements/create
お知らせを作成する。

announcements/delete
お知らせを削除する。

## ad
ad/list
広告の一覧を表示する。

ad/create
広告を作成する。

ad/update
広告を更新する。

ad/delete
広告を削除する。

## relays
relays/list
リレーの一覧を表示する。

relays/add
リレーを追加する。
