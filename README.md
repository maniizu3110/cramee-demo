# README.md

# cramee

塾講師と生徒のマッチングアプリです

[デモページ](https://cramee.link) #開発中

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
<img width="1127" alt="スクリーンショット 2022-02-17 0 55 46" src="https://user-images.githubusercontent.com/49385552/154303633-9d26efd8-dd7c-40c5-bc73-4688b9f8b37a.png">

### web UI

calendar
<img width="1428" alt="スクリーンショット_2022-02-17_0 47 14" src="https://user-images.githubusercontent.com/49385552/154303407-91ba4077-de9e-4ad9-9bda-52e6959ae713.png">

signuup
<img width="1416" alt="スクリーンショット_2022-02-17_0 47 51" src="https://user-images.githubusercontent.com/49385552/154303420-51275411-aa7b-4318-9b19-9ba20e474fa3.png">
