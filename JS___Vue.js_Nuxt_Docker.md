
## JS___Vue.js_Nuxt_Docker


* [Docker環境でLaravelを構築するまで、わずか15分。 - Qiita](https://qiita.com/hosono/items/dd404f3f074722ef989d)
* [Laravelの開発環境をDockerを使って構築する - Qiita](https://qiita.com/ucan-lab/items/17c806973e69792ada99)
* [Laravel5.6とVue.jsで簡単なシングルページアプリケーション - Qiita](https://qiita.com/shin1kt/items/8c98fb209de5caa9076d)
* [Laravel入門 - 使い方チュートリアル - - Qiita](https://qiita.com/sano1202/items/6021856b70e4f8d3dc3d)
* [Laravel Mixではじめるwebpack | CodeCode](https://codecodeweb.com/blog/535/)

─

* [Dockerでいい感じにPHP(Laravel)のローカル開発環境を作る - Qiita](https://qiita.com/igayamaguchi/items/aec8f2b15b203946a2c4)
* [Dockerを使ってLaravel開発環境構築 - Qiita](https://qiita.com/A-Kira/items/1c55ef689c0f91420e81)
* [アセットのコンパイル(Laravel Mix) 5.4 Laravel](https://readouble.com/laravel/5.4/ja/mix.html)
* [Laravel-Mix, BrowserSyncで画面を自動リロードする方法 - Qiita](https://qiita.com/tomo77777/items/5268eab2e98c7d1d4ad5)
* [Laravel Mix なら設定3行だけで webpack/Sass/JS のビルド環境ができました ｜ Tips Note by TAM](https://www.tam-tam.co.jp/tipsnote/html_css/post13444.html)
* [プライバシー エラー](https://techblog.scouter.co.jp/entry/2017/11/02/120748)
* [c-rtx.com](https://c-rtx.com/2015/09/22/laravel-on-sakura-rental-server/)
* [Laravelをさくらのレンタルサーバへデプロイ · M.Ike](https://mike-neko.github.io/blog/laravel-sakura/)
* [Laravelを本番サーバーにデプロイしてみた - Qiita](https://qiita.com/sskmy1024y/items/c2e434941400bd4ee82c)
* [【v2対応】Nuxt.jsとFirebaseを組み合わせて爆速でWebアプリケーションを構築する - Qiita](https://qiita.com/potato4d/items/cfddeb8732fec63cb29c)
* [Node.js: Nuxt.js + VuetifyでMySQLからTABLEを作る雛形 | マイヤーの開発ブログ](https://mayer.jp.net/?p=5515)
* [Nuxtで踏み出すフルスタックエンジニアへの道 - Qiita](https://qiita.com/gyarasu/items/a55b9864e137b4843e01)
* [Nuxt.js+Expressでとにかく簡単にORM - Crieit](https://crieit.net/posts/Nuxt-js-Express-ORM)
* [Node+Mysqlでブラウザにデータを表示させてみる - よちよち開発の日々](https://top-men.hatenablog.com/entry/2018/03/22/002623)


─

| メモ | メモ |
|:---|:---|
|ローカルでそのまま使うなら |npm run watch |
|Dockerなどを使用するなら |npm run watch-poll |
|Laravelのバージョンを確認するコマンド |php artisan -V<br>php artisan --version |
|Laravelの構成ファイル内で直接確認する |vendor￥laravel\framework\src\Illuminate\Foundation￥Application.php<br>Laravelインスタレーションのバージョンがクラスの最上部近くに、以下のように記述されています |
|プロジェクトにインストールされているパッケージを確認 |npm ls --depth=0 |


─

laravelは結局サーバー側にも環境作らなきゃいけないっぽいのでNUXTで制作予定。  
となるとNUXTからmysql・データベース接続する必要がある。

* [Nuxtで踏み出すフルスタックエンジニアへの道 - Qiita](https://qiita.com/gyarasu/items/a55b9864e137b4843e01)
* [Nuxt.js+Expressでとにかく簡単にORM - Crieit](https://crieit.net/posts/Nuxt-js-Express-ORM)
* [Express+MySQL+sequelizeでデータベース管理 - Qiita](https://qiita.com/y4u0t2a1r0/items/fb7a879cdd2a187bad29)


| メモ | メモ |
|:---|:---|
|Express |Nodeアプリケーションフレームワーク	https://expressjs.com/ja/ |
|mysql |DBとの接続	https://github.com/mysqljs/mysql |
|express-mysql-session |MySQLでのセッション管理	https://www.npmjs.com/package/express-mysql-session |
|log4js-node |ロギング	https://www.npmjs.com/package/express-mysql-session |
|config |環境ごとの設定ファイル	https://github.com/lorenwest/node-config |

Sequelize


<br><br><br>


* [docker-compose でMySQL環境簡単構築 - Qiita](https://qiita.com/A-Kira/items/f401aea261693c395966)


<br><br><br>


```
----------
01. test_databaseのSQLで実行（「test_table」が作成される）
----------
create table IF not exists `test_table`
(
 `id`               INT(20) AUTO_INCREMENT,
 `name`             VARCHAR(20) NOT NULL,
 `created_at`       Datetime DEFAULT NULL,
 `updated_at`       Datetime DEFAULT NULL,
    PRIMARY KEY (`id`)
) DEFAULT CHARSET=utf8 COLLATE=utf8_bin;

----------
02. test_databaseへ値を登録
----------
INSERT INTO test_table VALUES (1,'鈴木',null,null);
INSERT INTO test_table VALUES (2,'田中',null,null);
```


#### sqlファイルがあるgithub
* [gyarasu/mysql57-docker: docker-compose config for local env.](https://github.com/gyarasu/mysql57-docker)

#### その記事
* [Nuxtで踏み出すフルスタックエンジニアへの道 - Qiita](https://qiita.com/gyarasu/items/a55b9864e137b4843e01)


<br><br><br>

```
◆ 'NODE_ENV' は、内部コマンドまたは外部コマンド、
操作可能なプログラムまたはバッチ ファイルとして認識されていません。

https://codeday.me/jp/qa/20190407/573376.html
https://kotaeta.com/54356383


"dev": "NODE_ENV=development nuxt",
↓
"dev": "SET NODE_ENV=development & nuxt",

※windowsではこう書けば動く
```


<br><br><br>



#### nodeの最新版をインストール
* [ダウンロード | Node.js](https://nodejs.org/ja/download/current/)

#### npmの最新版をインストール
	npm i -g npm



<br><br><br>


* [node.js + mysqlでMySQLに接続し、テーブルからデータを取得する | Developers.IO](https://dev.classmethod.jp/articles/node-js-mysql-get-data-from-table-record/)
* [Node.jsのフレームワーク「Express」とは【初心者向け】 | TechAcademyマガジン](https://techacademy.jp/magazine/16119)
* [Nuxt.jsで自分に外部APIを立てるのにexpressなどは必要がない - Qiita](https://qiita.com/khsk/items/7bd4fb480c80124c00e2)
* [Node.jsとExpressとMySQLの簡単サンプル - Qiita](https://qiita.com/tiwu_dev/items/9ffc8e1fd1173b1a9e40)
* [node.js + mysqlでMySQLに接続し、テーブルからデータを取得する | Developers.IO](https://dev.classmethod.jp/articles/node-js-mysql-get-data-from-table-record/)
* [Node.jsでMySQL 8.0へ接続する - 不動の鳥の勉強記録](http://hiyo-ac.hatenablog.com/entry/2019/01/04/122044)
* [Node.jsとExpressとMySQLの簡単サンプル - Qiita](https://qiita.com/tiwu_dev/items/9ffc8e1fd1173b1a9e40)



<br><br><br>


```
※※※ expressとmysqlで取得されたデータをnuxtやvueで取り扱えるのか

package.jsonをプロジェクトに生成（オプション「-y」が全てyes回答のショートカット）
npm init -y

npm install express --save
npm install mysql --save
```



<br><br><br>



* [Nuxt.jsでさくっと静的サイトを作ってみよう - Photosynthesic blog](https://blog.photosynthesic.jp/2018/11/nuxt-js%E3%81%A7%E3%81%95%E3%81%8F%E3%81%A3%E3%81%A8%E9%9D%99%E7%9A%84%E3%82%B5%E3%82%A4%E3%83%88%E3%82%92%E4%BD%9C%E3%81%A3%E3%81%A6%E3%81%BF%E3%82%88%E3%81%86/)
* [Node+Mysqlでブラウザにデータを表示させてみる - よちよち開発の日々](https://top-men.hatenablog.com/entry/2018/03/22/002623)
* [Nuxt.js でバックもフロントもこれ一本 - Qiita](https://qiita.com/MaxBaconPower/items/298f95f751540b96d39b)




