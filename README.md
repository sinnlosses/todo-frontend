# todo-frontend

vue.js Nuxt.js による TODO アプリケーションのフロントエンド

# 環境構築

1. node 環境の準備をする

   1.1 node のバージョン管理ツール nodebrew をインストールする

   ```sh
   $ brew install nodebrew
   ```

   1.2 node のバージョン 18 系で最新のものを特定する

   ```sh
   $ nodebrew ls-remote
   ```

   1.3 1.2 で特定したバージョンをインストールする

   ```sh
   # v18.16.0 はあくまで例
   $ nodebrew install v18.16.0
   ```

   1.4 インストールできたか確認する

   ```sh
   $ node -v
   ```

2. npm よりも高速に動作するパッケージ管理ツール yarn をインストールする

   ```sh
   # -g をつけることでグローバルにインストールする
   $ npm install -g yarn
   ```

3. ライブラリインストール

   ```sh
   $ cd app
   $ yarn install
   ```

4. サーバー起動
   ```sh
   $ yarn dev
   ```
