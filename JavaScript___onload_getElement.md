
# JavaScript - ページ読み込み後の処理・要素取得

#### ◆ JavaScript

```javascript
window.onload = function(){
    // ページ読み込み後の処理
    // HTMLや画像など他の全てのデータの読み込みが完了した時に実行される。
    // 複数ある場合は、最後の処理が実行される。
}
```

```javascript
document.body.onload = function() {
    // 実行させたい処理;
    // window.onloadと同じ。（ブラウザによって挙動が違う場合あり）
}
```

```javascript
document.addEventListener('DOMContentLoaded', function() {
    // 実行させたい処理;
    // HTMLが読み込まれた時点で実行される。（画像などは待たない）
    // 複数ある場合はすべて実行される。
    // $(document).ready()とほぼ同じ動作。
});
```

```javascript
document.addEventListener('load', function() {
    // 実行させたい処理;
    // HTMLや画像など他の全てのデータの読み込みが完了した時に実行される。
    // 複数ある場合はすべて実行される。
    // $(window).on('load',とほぼ同じ動作。
});
```

```javascript
(function () {
    // 実行させたい処理;
    // 即時関数
    // HTMLの準備を待たずに実行する。
}());
```

```javascript
(() => {
    // 実行させたい処理;
})();
```

<br>



#### ◆ jQuery

```javascript
$(function(){
	// ページ読み込み後の処理
});
```

```javascript
jQuery(function(){
	// 処理
});
```

```javascript
jQuery(document).ready(function(){
	// 処理
});
```

```javascript
$(document).ready(function(){
	// ページ読み込み後の処理
});
```

```javascript
$(window).on('load resize',function(){
	// ページ読み込み後・windowリサイズ時の処理
});
```

<br><br><br>


## 参考link

###### ページ読み込み

* [ページ読み込み後に実行する関数の違い一覧（JavaScriptとjQuery） │ ブレインログ](https://brainlog.jp/post-470/)


###### 要素の取得

* [要素の取得方法まとめ - Qiita](https://qiita.com/amamamaou/items/25e8b4e1b41c8d3211f4)
* [【JavaScript】要素の取得方法(getElement、querySelector) - Qiita](https://qiita.com/tomokichi_ruby/items/c3ed6f6edbd5078ddf70)


