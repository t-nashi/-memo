
## ◆ Chrome - link
<table>
<thead>
<tr><th>内容</th><th>アドレス</th></tr>
</thead>
<tbody>
<tr><td>機能拡張</td><td>chrome://extensions/</td></tr>
<tr><td>リモートデバッグ</td><td>chrome://inspect/#devices</td></tr>
<tr><td>ブックマーク</td><td>chrome://bookmarks/</td></tr>
</tbody>
</table>

* [Inspect Devices - Chrome ウェブストア](https://chrome.google.com/webstore/detail/inspect-devices/pjpobmgdbnbegggcdgbljfgplleejmkb/)
* [【Google Chrome】「特別なURL」でトラシューや開発、管理に便利な機能を呼び出す（一覧あり）：Google Chrome完全ガイド - ＠IT](https://www.atmarkit.co.jp/ait/articles/1611/21/news027.html)

<br><br><br>


## ◆ Chrome - shortcut
<table>
<thead>
<tr><th>内容</th><th>Windows</th><th>Mac</th></tr>
</thead>
<tbody>
<tr><td>アドレスバーにカーソルを移動</td><td>Ctrl + L</td><td>⌘ + L</td></tr>
<tr><td>DevTools表示</td><td>Ctrl + Shift + I</td><td>⌘ + ⌥ + I</td></tr>
<tr><td>ブックマーク編集</td><td>Ctrl + Shift + O</td><td>⌘ + ⌥ + B</td></tr>
<tr><td>ブックマークバー表示・非表示</td><td>xxx</td><td>⌘ + Shift + B</td></tr>
</tbody>
</table>

* [【厳選】本当に使える Google Chrome のショートカットキー17個まとめ。](https://wayohoo.com/google-chrome/tips/useful-shortcut-key-list.html)

<br><br><br>











## ◆ [GetTabInfo](https://chrome.google.com/webstore/detail/gettabinfo/iadhcoaabobddcebhmheikmbcjcigjhc)

#### 参考link
* [Chromeでタブをたくさん開きがちな人に届け！作業効率を上げまくる拡張機能4選 | 株式会社LIG](https://liginc.co.jp/485496)


#### ▼ json01
```json
{"targetVersion":"2.0,1",
  "templates":
  [
    {
      "name":"・title(￥t)url",
      "value":"%%TITLE%%\t%%URL%%\n"
    },
    {
      "name":"・◆title(￥n)url",
      "value":"◆%%TITLE%%\n%%URL%%\n\n"
    },
    {
      "name":"・html-li",
      "value":"<li><a href=\"%%URL%%\">%%TITLE%%</a></li>\n"
    }
  ]
}
```

#### ▼ json02
```json
{
  "targetVersion": "2.0,1",
  "templates": [
    {
      "name": "・title(￥t)url",
      "value": "%%TITLE%%\t%%URL%%\n"
    },
    {
      "name": "・◆title(￥n)url",
      "value": "◆%%TITLE%%\n%%URL%%\n\n"
    },
    {
      "name": "・html-li",
      "value": "<li><a href=\"%%URL%%\">%%TITLE%%</a></li>\n"
    },
    {
      "name": "GitHub-Markdown-md",
      "value": "* [%%TITLE%%](%%URL%%)\n"
    }
  ]
}
```

<br><br><br>


## ◆ [Stylus](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne/related?hl=ja)

#### ▼ yahoo-mail-3column____________________
```css
#shellcontent {
    top: 30px !important;
}
#msg-list {
    width: 600px !important;
    height: 800px !important;
}
#msg-preview {
    top: 30px !important;
    left: 600px !important;
}
#rail-resize-hori {
    display: none !important;
}
#accordiontitlelist_bottom {
    display: none !important;
}
#shellnavigation,
body.accordiontitlelist_bottom {
    height: 800px !important;
}
```
