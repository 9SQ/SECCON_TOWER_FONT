# SECCON_TOWER_FONT

SECCON塔フォント

SECCON TOWER TrueType font

![sample](https://raw.githubusercontent.com/9SQ/SECCON_TOWER_FONT/master/seccon_tower_font.png)

## What is this

SECCON 2016 online CTFの問題 "PNG over Telegraph" にて登場する "SECCON TOWER" こと腕木通信塔が表現する36の形状を、対応する英数字記号に割り当てたフォントです。

大文字英数字(Jを除く)と、0〜9の数字、&(アンパサンド)が使用可能です。

* 36 symbols are assigned to A-I, K-Z, 0-9 and "&".
* "J" is not included because it is not defined in Chappe Code.

## Files

* seccon_tower.ttf - TrueType font
* seccon_tower.woff - Web font
* seccon_tower.woff2 - Web font (WOFF 2.0)
* svg/[A-IK-Z0-9&].svg - SVG(ver1.1) file(s)


## How to use (in your website)

### css/style.css

```css
@font-face {
  font-family: "SECCON_TOWER";
  src: url("seccon_tower.woff2") format('woff2'),
       url("seccon_tower.woff") format('woff');
}
.sctf {
  font-family: "SECCON_TOWER";
}
```

### index.html

```html
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="css/style.css">
  </head>
  <body>
    <p>SECCON TOWER FONT = <span class="sctf">SECCON TOWER FONT</span></p>
  </body>
</html>
```

## See also

* [SECCON 2016 online "PNG over Telegraph" : Eleclog.](http://eleclog.quitsq.com/2016/12/seccon-2016-online-png-over-telegraph.html)
* [SECCON TOWER 2016 - YouTube](https://www.youtube.com/watch?v=Y6voaURtKlM)
* [Sémaphore (communication) — Wikipédia](https://fr.wikipedia.org/wiki/S%C3%A9maphore_(communication))