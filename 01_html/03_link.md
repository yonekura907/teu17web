# ハイパーリンク

* `<a>`タグの属性値 href でリンク先のファイルを指定する。* リンク先のファイル指定はダブルコーテーションで括る。

&nbsp;
&nbsp;

## index.htmlからabout.htmlへのリンク
href属性に""(ダブルコーテーション)でファイル名を指定

![](https://yonekura907.github.io/myHtml/markup08@2x.png)


```
<a href="about.html">アバウト</a>
```

&nbsp;
&nbsp;

## about.htmlからindex.htmlへのリンク
href属性に""(ダブルコーテーション)でファイル名を指定

![](https://yonekura907.github.io/myHtml/markup09@2x.png)


```
<a href="index.html">ホーム</a>
```
&nbsp;
&nbsp;
&nbsp;

## 絶対パス　外部サイトへのリンク
href属性にhttpから始まるサイトURLを記述

![](https://yonekura907.github.io/myHtml/markup10@2x.png)


```
<a href="https://www.google.co.jp/">Google</a>
```
&nbsp;
&nbsp;
&nbsp;

別ウインドウで開きたい場合はtarget属性を指定する

```
<a href="https://www.google.co.jp/" target="_blank">Google</a>
```

&nbsp;
&nbsp;
&nbsp;

## index.htmlからaboutフォルダ内index.htmlへのリンク

href属性にフォルダ名/ファイル名を指定

![](https://yonekura907.github.io/myHtml/markup11@2x.png)


```
<a href="about/index.html">アバウト</a>
```

&nbsp;
&nbsp;
&nbsp;

## aboutフォルダ内index.htmlから一階層上のindex.htmlへのリンク
href属性に../ファイル名を指定

![](https://yonekura907.github.io/myHtml/markup12@2x.png)


```
<a href="../index.html">アバウト</a>
```
&nbsp;
&nbsp;
&nbsp;

### aboutフォルダ内index.htmlからworksフォルダ内のindex.htmlへのリンク
href属性に../ファイル名を指定

![](https://yonekura907.github.io/myHtml/markup13@2x.png)


```
<a href="../works/index.html">アバウト</a>
```