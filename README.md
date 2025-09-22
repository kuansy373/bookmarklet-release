# 一行化ブックマークレット

## vertical-text-size-color.js
### はじめに
・AI（ChatGPTの主に4o）を駆使して作りました。<br>
ほぼコピペするだけで作ったので、私はプログラミング素人とも名乗れない、プログラミング未経験者です。<br>
・みもねる氏の｢青空一行文庫ブックマークレット｣を知り、使ってみて、｢更にこれが出来たらすごいんじゃないか？｣という機能を付け加えてていきました。<br>
<br>
### 対象サイト
対象サイトは青空文庫に加え、｢小説家になろう・カクヨム・アルファポリス」です。
<br><br>
<pre><code>javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/kuansy373/bookmarklet-release@v1.1.3/vertical-text-size-color.js';document.body.appendChild(s);})();
</code></pre>
<br>
最初実行したときは、このような感じ。
<br><br>
<img src="images/photo1.jpg" alt="Example Bookmarklet" width="300">
<br>
右上、左上にうっすらとある〇や□、△をタップするといろいろ設定できます。。
<br><br>
<img src="images/photo2.jpg" alt="Example Bookmarklet" width="300">
<br>
設定するとこんな感じにできます。左右に伸びてるのはスクロールバーの当たり判定です。
<br><br>
<img src="images/photo3.jpg" alt="Example Bookmarklet" width="300">

### 強み
自動スクロールができる。色を自由に変えられる。長文に対応してる。
### 弱み
カクつきが発生する。(たぶんChromeがいちばん少ないです)<br>
フォントサイズを変更するとスクロール位置が変わる(ページ内検索をしおり替わりにするとよい)。

### 注意点
webページが広告まで完全に読み込んでからブックマークレットを実行してください。<br>
自動スクロールのカクつきがかなり発生します。Chromeを使うか、スクロールバーに触れていたら軽減します。フォントをいじるとカクつきやすいです。<br>
ここに載せているjavascript:は最新のタグにしています。
<br>
## おまけ
### color.js
<pre><code>javascript:(function(){var s=document.createElement('script');s.src='https://cdn.jsdelivr.net/gh/kuansy373/bookmarklet-release@v1.1.3/color.js';document.body.appendChild(s);})();
</code></pre><br>
