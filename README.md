# README.md

# cramee

塾講師と生徒のマッチングアプリです

URL:demo.cramee.link

デモ用アカウント情報

メールアドレス：demo@gmail.com

パスワード：demo1234

### 概要・使用方法

- [x]  講師がスケジュールに空いている時間を登録
- [x]  生徒が講師一覧から好きな講師を選択
- [x]  講師が承認すると予約が完了
- [ ]  時間になったらzoomリンクに入ると授業開始
- [ ]  月末に決済処理

## 使用技術

### フロント

- nuxt
- vue
- vuetify

### サーバー

- golang
- echo
- mysql
- nginx
- zoom API(フロント未実装)
- stripe API(フロント未実装)

### インフラ

- aws
- github Actions
- docker
- kubernetes
- cloudformation

構成

### web UI

calendar

signuup