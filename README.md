# Dip x Rails Sandbox

## 環境

- Rubyインストール済み
- Docker Composeインストール済み

## セットアップ

```
gem install dip
dip compose build
dip provision
```

```
dip rails s
```

http://localhost:3000/ にアクセス

## テスト

```
dip minitest
```

## ターミナルに入る

```
dip sh
```

## コンテナ停止

```
dip down
```

## 参考文献
- Docker Compose環境作成
  - [Rails 6.1のDocker開発環境構築をEvil Martians流にやってみた（更新）](https://techracho.bpsinc.jp/hachi8833/2021_03_25/83450)
  - [クジラに乗ったRuby: Evil Martians流Docker+Ruby/Rails開発環境構築（翻訳）](https://techracho.bpsinc.jp/hachi8833/2021_04_20/79035)

- Dip開発環境作成
  - [docker-composeを便利にするツール「dip」を使ってみた](https://techracho.bpsinc.jp/hachi8833/2021_04_14/83481)
  - [Docker ComposeとDipで開発用コンテナを再利用可能にする（翻訳）](https://techracho.bpsinc.jp/hachi8833/2021_05_20/107397)
