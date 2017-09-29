# HTMLの役割

![](https://yonekura907.github.io/myHtml/htmlcssjs@2x.png)

&nbsp;
&nbsp;
&nbsp;


# HTMLとは

![](https://yonekura907.github.io/myHtml/markup01@2x.png)

ユーザーは文字の大きさや色使い、レイアウトで見出しや本文といった文章内容の意味付けが分かるがブラウザはコンピュータなので理解できない。
ブラウザに内容を伝えるための **しるしづけ(マークアップ)**を行なう。


&nbsp;
&nbsp;

![](https://yonekura907.github.io/myHtml/markup02@2x.png)

&nbsp;

しるしを**タグ**と呼び。その内容を**要素**と呼ぶ

![](https://yonekura907.github.io/myHtml/markup03@2x.png)

&nbsp;
&nbsp;
----
&nbsp;
&nbsp;


# HTMLコーディング

### DOCTYPE
HTMLのバージョンを表す。

![](https://yonekura907.github.io/myHtml/markup04@2x.png)
タグ内の単語間は半角スペースを使う。全角スペースを記述するとエラーを起こす

&nbsp;
&nbsp;

### html要素
HTMの開始と終了を記述する

![](https://yonekura907.github.io/myHtml/html02@2x.png)

&nbsp;
&nbsp;

#### タグと属性
![](https://yonekura907.github.io/myHtml/markup05@2x.png)

htmlタグ内で使用する言語は日本語という意味" "（ダブルコーテーション）の中はhtml以外の言語が使える（例：全角の日本語や他のプログラム言語）

&nbsp;
&nbsp;

### head / body 要素
* headはドキュメントに関する情報（ブラウザの枠内には表示されない）
* bodyはブラウザのページ内に表示される内容。

![](https://yonekura907.github.io/myHtml/html03@2x.png)

```
<!DOCTYPE html>
<html lang="ja">
<head>
   
</head>
<body>
    
</body>
</html>
```

&nbsp;
&nbsp;

### title 要素
ブラウザのウインドウ（タブ）に表示されるページのタイトル
![](https://yonekura907.github.io/myHtml/html04@2x.png)

```
<!DOCTYPE html>
<html lang="ja">
<head>
    <title>SHELF CAFE</title>
</head>
<body>
    
</body>
</html>
```

&nbsp;
&nbsp;

### meta charset
htmlファイルの文字コード

![](https://yonekura907.github.io/myHtml/html05@2x.png)

```
<!DOCTYPE html>
<html lang="ja">
	<head>
	    <title>SHELF CAFE</title>
	    <meta charset="UTF-8">
	</head>
	<body>
	    
	</body>
</html>
```
&nbsp;
&nbsp;
#### その他のmeta要素
description 文書の説明

```
<meta name="description" content="Shelf Cafeは本と音楽が心地良いカフェです">
```
Keywords キーワードの指定

```
<meta name="Keywords" content="Shelf Cafe, シェルフカフェ, 読書, 本, カフェ"> 
```

&nbsp;
&nbsp;
----
&nbsp;
&nbsp;

# 見出しと段落

ページ内の見出しレベル(大見出し、中見出し、小見出し)に応じて h1~h6までの数字を使用する。段落、本文、意味付けのない一般文章にはpタグを使用する。

```
<h1>ようこそ、SHELF CAFEへ</h1><p>本と音楽が心地良いカフェ。</p>
<h2>ブックフェア</h2><p>書物と活字を販売しています。</p>
```

&nbsp;
&nbsp;

![](https://yonekura907.github.io/myHtml/site01@2x.png)




&nbsp;
&nbsp;
----
&nbsp;
&nbsp;


