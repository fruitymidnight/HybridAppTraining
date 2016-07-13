# サーバアプリ #
## Express ##
NodeJS のサーバアプリフレームワークの Express を利用する。

- 参考
    - https://gist.github.com/mitsuruog/fc48397a8e80f051a145

### 雛形作成 ###
Express が提供している雛形作成ツールをインストール。
```
$ npm install -g express-generator
```


雛形の作成。今回は "server" という名前のアプリを作成。
```
$ express server
$ cd server && npm install  ## 依存関係のインストール
```

### json API の作成 ###

以下のようなAPIを作成する

- エントリポイント
    - http://[hostname]/json/1/data?param1=hoge&param2=fuga
- メソッド
    - GET/POST





## 作成時のログ ##

```
$ express server

   create : server
   create : server/package.json
   create : server/app.js
   create : server/public
   create : server/public/javascripts
   create : server/routes
   create : server/routes/index.js
   create : server/routes/users.js
   create : server/public/images
   create : server/public/stylesheets
   create : server/public/stylesheets/style.css
   create : server/views
   create : server/views/index.jade
   create : server/views/layout.jade
   create : server/views/error.jade
   create : server/bin
   create : server/bin/www

   install dependencies:
     $ cd server && npm install

   run the app:
     $ DEBUG=server:* npm start

$ cd server && npm install
```
