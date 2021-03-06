## ■ 基礎

#### ▼ Vue.js
Jsフレームワーク
<br><br>

#### ▼ vue-cli
VueCLIはVue.js開発できるようにいろいろ準備してくれるすげーやつ。

* [VueCLIからVue.js入門①【VueCLIで出てくるファイルを概要図で理解】 - Qiita](https://qiita.com/po3rin/items/3968f825f3c86f9c4e21)
* [Vue.js を vue-cli を使ってシンプルにはじめてみる - Qiita](https://qiita.com/567000/items/dde495d6a8ad1c25fa43)
<br><br>



#### ▼ vuex
Vue.js アプリケーションのための 状態管理パターン + ライブラリ

* [Vuex とは何か？ | Vuex](https://vuex.vuejs.org/ja/)
<br><br>



#### ▼ Nuxt.js
Vue.js アプリケーションを構築するためのフレームワーク
<br><br>



| 名称 | 解説 |
|:---|:---|
|Vue Router |シングルページアプリケーションを実現するためのルーティングプラグイン |
|Vuex |大規模なWebアプリケーションを構築するための状態管理プラグイン |
|Vue Loader |高度なコンポーネント機能を利用するためのwebpack向けのローダーライブラリ |
|Vue CLI  |Webアプリケーションを構築するためのプロジェクト構成の雛形生成やプロトタイピングにおいて設定なしビルドを行うためのコマンドラインツール |
|Vue DevTools |Vue.jsアプリケーションをブラウザの開発ツールでデバッグするためのツール |
|Nuxt.js  |シングルページアプリケーションとサーバーサイドレンダリングに対応したVue.jsアプリケーションを作成するためのフレームワーク |
|Weex |Vue.jsの構文でiOS、Androidアプリケーションを作成するためのフレームワーク |
|Onsen UI  |モバイル向けWebアプリケーションを作成するためのフレームワーク |
|Awesome Vue |Vue.jsに関連するオープンソースプロジェクトやVue.jsが使われているWebサイトやアプリケーションなどの情報がユーザーによって共有される公式サイト |
|Vue Curated |Vue.jsコアチームが厳選したプラグイン、ライブラリ、フレームワークなどを検索できる公式サイト |
|MVVMパターン |ソフトウェアアーキテクチャパターンの一種（Model-View-ViewModel） |



<br><br><br>


#### オプション名、内容
Vue.js アプリケーションを構築するためのフレームワーク

| 名称 | 解説 |
|:---|:---|
|data |UIの状態・データ |
|el |Vueインスタンスをマウントする要素 |
|filters |データを文字列と成形する |
|methods |イベントが発生した時などの振る舞い |
|computed |データから派生して算出される値 |
|Appendix | |
|Electron（ブラウザ？） |◆ Console.assert() - Web API｜MDN<br>https://developer.mozilla.org/ja/docs/Web/API/console/assert<br>Console.assert() |
|コンストラクタ |オブジェクトを生成するための関数（new演算子を使う）<br>生成されたオブジェクトをVueインスタンスと呼ぶ |
|To get started |cd my-portfolio-sample<br>npm run dev |
|To build & start for production |cd my-portfolio-sample<br>npm run build<br>npm start |
|Index ページ |http://localhost:3000 |
|About ページ |http://localhost:3000/about |
|404 ページ |http://localhost:3000/hogehoge |

<br><br><br>


#### ▼ index.html
```
<body>
  <div id="app">
    <!-- ここにテンプレートを書いていく -->
  </div>
</body>
```



#### ▼ main.js（new Vue）
```
const app = new Vue({
  el: '#app',
  data: {
    // 使用するデータ
  },
  methods: {
    // 使用するメソッド
  }
})
```


#### ▼ export default
```
export default {
  name: 'app',
  data () {
    return {
      // 使用するデータ
    }
  }
}
```



<br><br><br>











## ■ jQuery → Vue.js

* [-memo/JavaScript.txt at master · t-nashi/-memo](https://github.com/t-nashi/-memo/blob/master/JavaScript.txt)
* [WebデザイナーのためのVue.js事始め | Webクリエイターボックス](https://www.webcreatorbox.com/tech/first-vuejs)
* [jQuery から Vue.js へのステップアップ - Qiita](https://qiita.com/mio3io/items/e7b2596d06b8005e8e6f)
* [SPAだけじゃない！Vue.js[1]　jQueryをVue.jsに書き換えてみる | 株式会社LIG](https://liginc.co.jp/373882)
* [初めてのVue.js（jQuery脳からの移行をメインに） - Qiita](https://qiita.com/hoshimado/items/12df6fa00c102d087960)
* [脱jQuery .addClass() .hasClass() .removeClass() .toggleClass() | q-Az](https://q-az.net/none-jquery-addclass-has-remove-toggle/)
* [脱jQueryの道その２:あの機能は素のJavaScriptでどうやるんだろ編 | webOpixel](https://www.webopixel.net/javascript/1516.html)



<br><br><br>











## ■ Nuxt

#### Nuxtの事始めに良い
* [【Ch.1】 Nuxt とは？動かして理解する【Nuxt de Portfolio】 | 株式会社LIG](https://liginc.co.jp/449551)
* [Nuxt.jsで「render function or template not defined in component」 - Qiita](https://qiita.com/shozzy/items/9ea438a1eea3d5fc3431)
* [Nuxt.js v2.4.0以上でnuxt-sass-resources-loaderを使ってはいけない - Qiita](https://qiita.com/tsukue/items/e3565d889ebe7b078748)

<br>

#### nuxtのバージョン調べる
```
npx nuxt -v
```



```
◆ Vue.js&Nuxt.js超入門｜サポート｜秀和システム
https://www.shuwasystem.co.jp/support/7980html/5659.html

▼ 2021/01/06wed時点の各バージョン
・nuxt/cli： v2.14.12
・node： v12.16.1
・npm： 6.9.0


▼ インストールコマンド
npx create-nuxt-app <project-name>
npm init nuxt-app <project-name>
※ npx（npx は npm 5.2.0 以降だとデフォルトで同梱されています）か、v6.1 の npm か yarn がインストールされていることを確認してください


▼ vuex-persistedstateプラグインインストール（Vuexステートをローカルストレージへ保管）
npm i vuex-persistedstate

▼ axiosをインストール
npm i axios --save

▼ Firebase APIをインストール
npm i firebase --save

▼ sass関連
npm i node-sass sass-loader --save-dev
npm install --save-dev reset-css
npm install --save-dev @nuxtjs/style-resources




▼ package.json
{
  "name": "my-app",
  "scripts": {
    "dev": "nuxt"
  },
  "dependencies": {
    "nuxt": "^2.14.12"
  }
}







```





<br>

## vue-cliとNuxtの比較をざっくり知るのに良い

* [NUXT いるのかどうか (Vue CLI 3 との比較) - Qiita](https://qiita.com/macoshita/items/bf295a1e0f5fefff3d8e)


```
▼ メモ

ルーティング試したい

エラーログの場所
C:\Users\（ユーザー名）\AppData\Roaming\npm-cache\_logs

asyncData

axios

◆Vue.js #007 – Nuxt.jsとaxiosでAPI取得 | dayjournal memo
https://day-journal.com/memo/vue-js-007/

```


<br><br><br>













## ■ SSRせずプリレンダリング

* [SSRしないNuxt.jsでページロード時に非同期部分を更新する方法 | なすびブログ](https://blog.nasbi.jp/programming/frontend/javascript/ssr%E3%81%97%E3%81%AA%E3%81%84nuxt-js%E3%81%A7%E3%83%9A%E3%83%BC%E3%82%B8%E3%83%AD%E3%83%BC%E3%83%89%E6%99%82%E3%81%AB%E9%9D%9E%E5%90%8C%E6%9C%9F%E9%83%A8%E5%88%86%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%99/)
* [Vue.js - nuxt.js　で取得したjsonデータを表示する方法｜teratail](https://teratail.com/questions/186439)
* [NuxtのasyncDataで静的ファイルを読み込む || log.pocka.io](https://log.pocka.io/ja/posts/nuxt-asyncdata-static-file-code-splitting/)
* [Nuxt.js(v2)で静的なJSONファイルを読み込み、いろんな所で使う。 - Qiita](https://qiita.com/amishiro/items/b09f9038ee3ebfee33d4)
* [Nuxt.jsでVuexをモジュールモードで利用する](https://doitu.info/blog/5ad8859de59645002dde9c80)
* [export default ってなに？ - Qiita](https://qiita.com/masash49/items/e71319eef82619d19cd8)
* [Vue の export default と import - 山崎屋の技術メモ](https://www.shookuro.com/entry/2018/09/22/172636)
* [Vue.jsの書き方実例集(随時追加)※逆引きリファレンス的な - Qiita](https://qiita.com/Yorinton/items/a0144c34e4edb0777493)
* [基礎から学ぶ Vue.js](https://cr-vue.mio3io.com/)

```
export default

computed 		 // 関数として実装、参照時はプロパティとして機能
methods 		 // 
components 		 // 
asyncData 		 // 

↑ Vueコンストラクタのオプションオブジェクト
```
* [Vue.js｜主なオプション(data, computed, filter, props) - わくわくBank](https://www.wakuwakubank.com/posts/504-vue-sfc-script/)
* [【Vue.js】Vue.jsで指定回数の処理を実行するfor文 | HAFILOG](https://hafilog.com/vue-for-loop)



















<br><br><br>

## ■ チュートリアル

◆Vue.jsを用いたサンプルが数多くまとめられている「Vue.js Examples」 | NxWorld
https://www.nxworld.net/services-resource/vuejsexamples.html?utm_content=bufferd3cd3&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer

◆Vue.jsの勉強にもいい！UIコンポーネントやインタラクションを実装するチュートリアルがまとめられた -Vue.js Examples | コリス
https://coliss.com/articles/build-websites/operation/javascript/vuejs-examples.html

◆サーバーサイドエンジニアがじっくり学ぶVue.jsチュートリアル【2. Introduction】 | Developers.IO
https://dev.classmethod.jp/articles/vuejs-tutorials-of-db-engineer-2/

◆ワイ「何でそんな小っさいコンポーネント作ってるん？ｗ」 - Qiita
https://qiita.com/Yametaro/items/e8cb39b1a20b762bfafa



<br><br><br>

## ■ チートシート

◆最新版のチートシート！Vue.jsのよく使用するイベントや構文がまとめられたフロントエンド制作者用チートシート | コリス
https://coliss.com/articles/build-websites/operation/javascript/cheat-sheet-of-vue.html

◆Vue.js Cheat Sheet
https://flaviocopes.com/vue-cheat-sheet/





<br><br><br>

## ■ 2020/07/26 sun

* [Vue.js 入門 （htmlベースで基本機能を知ろう編） - Qiita](https://qiita.com/isihigameKoudai/items/6718237cd8a971442e2d)
* [ToDoリストを作りながら学習しよう！ | 基礎から学ぶ Vue.js](https://cr-vue.mio3io.com/tutorials/todo.html#step1-%E3%82%A4%E3%83%B3%E3%82%B9%E3%82%BF%E3%83%B3%E3%82%B9%E3%81%AE%E4%BD%9C%E6%88%90)
* [Vue.jsの「export default」と「new Vue」の書き方 – myMemoBlog by 256hax](https://blog.tanebox.com/archives/470/)
* [【Vue.js】イベントハンドリングをサンプルを作りながら理解する - Qiita](https://qiita.com/b1san/items/6bc0be17cd6ed687520c)
* [jQueryでよく使う動きをVue.jsでやってみる - Qiita](https://qiita.com/g-taguchi/items/9f97f2172aa048934f1c)
* [JavaScript - 複数のv-on:clickを記述するとクリックした要素を取得できない｜teratail](https://teratail.com/questions/134322)

─

* [「Vue.js」子要素と親要素のクリック イベントを併発しない方法！](https://hasethblog.com/blog-entry-625.html)
* [【Vue.js入門】v-on、v-forを使ってみよう！ - Qiita](https://qiita.com/watsuyo_2/items/bda8f2673cf49de4421b)
* [JavaScript classListでクラス属性を操作するゾ - かもメモ](https://chaika.hatenablog.com/entry/2019/02/15/090000)
* [短縮記法でちゃちゃっと書こう。（Vue.js始めるおれおれアドベントカレンダー2016 – 15日目） | Ginpen.com](https://ginpen.com/2016/12/15/vue-shorthands/)
* [Vuejs dataプロパティに動的に値を追加する方法（とJSの基本を理解してなかったという話) - SIerだけど技術やりたいブログ](https://www.kimullaa.com/entry/2017/07/24/224951)
* [Vueのv-bind:classの書き方・使い方について解説 | ELOOP（イーループ） - 開発課題に取り組んで身につける実践型プログラミング学習サービス](https://www.e-loop.jp/knowledges/5/)
* [Vue.jsでtoggleClass | ITかあさん](http://www.kaasan.info/archives/4270)
* [Vue.js試行用HTMLテンプレートをつくってみた | // もちぶろ](https://slash-mochi.net/?p=1603)

─

* [ToDoリストを作りながら学習しよう！ | 基礎から学ぶ Vue.js](https://cr-vue.mio3io.com/tutorials/todo.html#step1-%E3%82%A4%E3%83%B3%E3%82%B9%E3%82%BF%E3%83%B3%E3%82%B9%E3%81%AE%E4%BD%9C%E6%88%90)
* [Vue.jsミニハンズオン（TODOリスト作成） - Qiita](https://qiita.com/moonglows76/items/358ef3cd1566c38ece3a)











<br><br><br>

## ■ V2 - guide

* [Vue.js](https://jp.vuejs.org/)
* [はじめに — Vue.js](https://jp.vuejs.org/v2/guide/index.html)
* [テンプレート構文 — Vue.js](https://jp.vuejs.org/v2/guide/syntax.html)
* [コンポーネントの基本 — Vue.js](https://jp.vuejs.org/v2/guide/components.html)
* [クラスとスタイルのバインディング — Vue.js](https://jp.vuejs.org/v2/guide/class-and-style.html)
* [リストレンダリング — Vue.js](https://jp.vuejs.org/v2/guide/list.html)



<br><br><br>

## ■ xxxxx

* [【第1回】Vue.js 入門 〜Hello World編〜 - 株式会社ライトコード](https://rightcode.co.jp/blog/information-technology/vue-js-introduction-hello-world)
* [【第2回】Vue.js 入門 〜ディレクティブ編〜 - 株式会社ライトコード](https://rightcode.co.jp/blog/information-technology/vue-js-introduction-directive)
* [1週間でVue.jsをマスターしようと思った時に参考にしたサイト - Qiita](https://qiita.com/mimoe/items/56784c9d17ed34ee7533)
* [最新版のチートシート！Vue.jsのよく使用するイベントや構文がまとめられたフロントエンド制作者用チートシート | コリス](https://coliss.com/articles/build-websites/operation/javascript/cheat-sheet-of-vue.html)
* [Vue.jsの勉強にもいい！UIコンポーネントやインタラクションを実装するチュートリアルがまとめられた -Vue.js Examples | コリス](https://coliss.com/articles/build-websites/operation/javascript/vuejs-examples.html)
* [Vue.jsを用いたサンプルが数多くまとめられている「Vue.js Examples」 - NxWorld](https://www.nxworld.net/vuejsexamples.html?utm_content=bufferd3cd3&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* [Vue.js関連の各種リソースがまとめられた「VueToolbox」 - NxWorld](https://www.nxworld.net/vuetoolbox.html?utm_content=buffere0d96&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* [Nuxt.js のような自動ルーティングを可能にする Vue CLI プラグインを作った | Web 猫](https://katashin.info/2018/07/16/233)
* [t-nashi/-memo: 各技術ごとのメモ](https://github.com/t-nashi/-memo/tree/master)
* [nuxtの検索結果 | 株式会社LIG](https://liginc.co.jp/?s=nuxt)
* [Nuxt.jsでWebサイト制作 [1] 導入編 | 株式会社LIG](https://liginc.co.jp/416085)
* [SPAだけじゃない！Vue.jsの検索結果 | 株式会社LIG](https://liginc.co.jp/?s=SPA%E3%81%A0%E3%81%91%E3%81%98%E3%82%83%E3%81%AA%E3%81%84%EF%BC%81Vue.js)
* [Webサイト制作のチュートリアル連載「Nuxt de Portfolio（全５回）」を始めます！ | 株式会社LIG](https://liginc.co.jp/449537)
* [算出プロパティとウォッチャ — Vue.js](https://jp.vuejs.org/v2/guide/computed.html)
* [【Vue.js】computedとmethodsの違い - りんごとバナナとエンジニア](https://udomomo.hatenablog.com/entry/2017/12/11/213904)
* [Page Not Found](https://mk-engineer.com/nuxt-start)

─

* [複数のページを切り替える、Nuxt.jsのルーティング機能を学ぼう (1/3)：CodeZine（コードジン）](https://codezine.jp/article/detail/11828)
* [画面要素を再利用できる、Vue.jsのコンポーネント機能を学ぼう (1/3)：CodeZine（コードジン）](https://codezine.jp/article/detail/11856)
* [Vue.js設計地図 〜設計概念の依存関係からフロントエンド設計を見つめ直す〜](https://tech.plaid.co.jp/architecture_frontend_modeling/)
* [JavaScript UIフレームワーク「Vue.js」で「Wijmo（ウィジモ） 5」のリッチなUI部品を使おう (1/3)：CodeZine（コードジン）](https://codezine.jp/article/detail/11582)
* [「Vue.js」でWebページを作成できるフレームワーク「Nuxt.js」最初の一歩 (1/3)：CodeZine（コードジン）](https://codezine.jp/article/detail/11566)

─

* [ルーティング — Vue.js](https://jp.vuejs.org/v2/guide/routing.html)
* [ルーティングとコード分割 | Vue SSR ガイド](https://ssr.vuejs.org/ja/guide/routing.html)
* [動的ルートマッチング | Vue Router](https://router.vuejs.org/ja/guide/essentials/dynamic-matching.html)
* [Vue.jsでSPA - [3] vue-routerでルーティング - Qiita](https://qiita.com/narutaro/items/74178f4ea031b0ccfa44)

─

* [vue-cliの導入から新規でVue.jsのプロジェクト作成とビルド方法まとめ | オウンドメディア | 大阪市天王寺区SOHOホームページ制作 | デザインサプライ-DesignSupply.-](https://designsupply-web.com/media/knowledgeside/4632/)
* [vue-cli 3系への移行と新規Vue.jsプロジェクト作成とビルド方向まとめ | オウンドメディア | 大阪市天王寺区SOHOホームページ制作 | デザインサプライ-DesignSupply.-](https://designsupply-web.com/media/knowledgeside/4639/)
* [Vue-routerを使って、SPAをシンプルにはじめてみる - Qiita](https://qiita.com/567000/items/d6a7c694a370dc92e774)
* [Scrapbox](https://scrapbox.io/vue-yawaraka/webpack(vue-cli)%E3%81%AF%E4%BD%95%E3%82%92%E3%81%97%E3%81%A6%E3%81%8F%E3%82%8C%E3%82%8B%E3%82%82%E3%81%AE%E3%81%AA%E3%81%AE%E3%81%8B)
* [NUXT いるのかどうか (Vue CLI 3 との比較) - Qiita](https://qiita.com/macoshita/items/bf295a1e0f5fefff3d8e)
* [Vue.jsでSPA - [1] Element UIでベースの画面をつくる - Qiita](https://qiita.com/narutaro/items/50d0e4714f93279502c9)



<br><br><br>

## ■ Vue.js入門 基礎から実践アプリケーション開発まで

* [Vue.js入門 基礎から実践アプリケーション開発まで | 川口 和也, 喜多 啓介, 野田 陽平, 手島 拓也, 片山 真也 |本 | 通販 | Amazon](https://www.amazon.co.jp/dp/4297100916)
* [vuejs/vue-router: 🚦 The official router for Vue.js.](https://github.com/vuejs/vue-router)
* [vuejs/vuex: 🗃️ Centralized State Management for Vue.js.](https://github.com/vuejs/vuex)
* [vuejs/vue-loader: 📦 Webpack loader for Vue.js components](https://github.com/vuejs/vue-loader)
* [vuejs/vue-cli: 🛠️ Standard Tooling for Vue.js Development](https://github.com/vuejs/vue-cli)
* [vuejs/vue-devtools: ⚙️ Browser devtools extension for debugging Vue.js applications.](https://github.com/vuejs/vue-devtools)
* [Nuxt.js - The Intuitive Vue Framework](https://nuxtjs.org/)
* [WEEX](https://weex.incubator.apache.org/)
* [Onsen UI 2: Beautiful HTML5 Hybrid Mobile App Framework and Tools - Onsen UI](https://onsen.io/)
* [vuejs/awesome-vue: 🎉 A curated list of awesome things related to Vue.js](https://github.com/vuejs/awesome-vue)
* [Vue Curated](https://curated.vuejs.org/)





