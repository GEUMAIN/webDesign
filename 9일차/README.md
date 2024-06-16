### 9일차

### 레이아웃 F형

## 레이아웃 F-1

---

![깃헙1](https://github.com/GEUMAIN/webDesign/assets/128437656/f4f22ffa-7fc6-41a1-a362-e7b5a7470584)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 F-1</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <header id="header">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </header>

        <article id="slider">이미지 슬라이드
            <div class="link">링크</div>
        </article>

        <section id="contents">
            <article class="banner">배너</article>
            <article class="notice">공지사항/갤러리</article>
        </section>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">
                <div class="footer2-1">하단 메뉴</div>
                <div class="footer2-2">COPYRIGHT</div>
            </div>
        </footer>

    </div>

</body>

</html>
```

---

### CSS

```css
* {
    font-family: "nanumSquareNeo";
    text-align: center;
    margin: 0;
    padding: 0;
}

#wrap {
    width: 100%;
}

#header {
    width: 1340px;
    margin: 0 auto;
    display: flex;
}

#header .logo {
    width: 20%;
    height: 100px;
    background-color: #efefef;
}

#header .nav {
    width: 80%;
    height: 100px;
    background-color: #e3e3e3;
}

#slider {
    width: 100%;
    height: 350px;
    background-color: #d9d9d9;
    position: relative;
}

#slider .link {
    width: 1340px;
    height: 100px;
    background-color: #d1d1d1;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
}

#contents {
    width: 1340px;
    margin: 0 auto;
}

#contents .banner {
    width: 100%;
    height: 150px;
    background-color: #c7c7c7;
}

#contents .notice {
    width: 100%;
    height: 300px;
    background-color: #bbbbbb;
}

#footer {
    width: 1340px;
    height: 120px;
    margin: 0 auto;
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 120px;
    background-color: #b8b8b8;
}

#footer .footer2 {
    width: 80%;
    height: 120px;
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 60px;
    background-color: #b1b1b1;
}

#footer .footer2 .footer2-2 {
    width: 100%;
    height: 60px;
    background-color: #a3a3a3;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

.logo,
.nav,
.banner,
.notice,
.link,
.footer1,
.footer2-1,
.footer2-2,
#slider {
    display: flex;
    align-items: center;
    justify-content: center;
}

#contetns {
    line-height: 40px;
}
```

---

## 레이아웃 F-2

---

![깃헙2](https://github.com/GEUMAIN/webDesign/assets/128437656/df0bee64-7d92-4555-875b-2462a2295c57)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 F-2</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <header id="header">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </header>

        <article id="slider">이미지 슬라이드
            <div class="link">링크</div>
        </article>

        <section id="contents">
            <article class="notice">공지사항</article>
            <article class="gallery">갤러리</article>
        </section>

        <footer id="footer">
            <div class="footer1">COPYRIGHT</div>
            <div class="footer2">
                <div class="footer2-1">하단 메뉴</div>
                <div class="footer2-2">패밀리사이트</div>
            </div>
        </footer>
    </div>
</body>

</html>
```

---

### CSS

```css
* {
    font-family: "nanumSquareNeo";
    text-align: center;
    margin: 0;
    padding: 0;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#wrap {
    width: 100%;
}

#header {
    width: 1340px;
    margin: 0 auto;
    display: flex;
}

#header .logo {
    width: 20%;
    height: 100px;
    background-color: #efefef;
}

#header .nav {
    width: 80%;
    height: 100px;
    background-color: #e3e3e3;
}

#slider {
    width: 100%;
    height: 350px;
    background-color: #d9d9d9;
    position: relative;
}

#slider .link {
    width: 1340px;
    height: 100px;
    background-color: #d1d1d1;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
}

#contents {
    width: 1340px;
    margin: 0 auto;
    display: flex;
}

#contents .notice {
    width: 50%;
    height: 300px;
    background-color: #c7c7c7;
}

#contents .gallery {
    width: 50%;
    height: 300px;
    background-color: #bbbbbb;
}

#footer {
    width: 1340px;
    height: 120px;
    margin: 0 auto;
    display: flex;
}

#footer .footer1 {
    width: 80%;
    height: 120px;
    background-color: #b8b8b8;
}

#footer .footer2 {
    width: 20%;
    height: 120px;
}

#footer .footer2-1 {
    width: 100%;
    height: 60px;
    background-color: #b1b1b1;
}

#footer .footer2-2 {
    width: 100%;
    height: 60px;
    background-color: #a3a3a3;
}

.logo,
.nav,
.link,
.gallery,
.notice,
.footer1,
.footer2-1,
.footer2-2,
#slider {
    display: flex;
    align-items: center;
    justify-content: center;
}

#contents {
    line-height: 400px;
}
```

---

## 레이아웃 F-3

---

![깃헙3](https://github.com/GEUMAIN/webDesign/assets/128437656/3b718311-0dc4-4a08-831c-78488d0a47ea)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 F-3</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <header id="header">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </header>

        <article id="slider">이미지 슬라이드
            <div class="link">링크</div>
        </article>

        <section id="contents">
            <article class="banner">배너</article>
            <article class="notice">공지사항/갤러리</article>
        </section>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">
                <div class="footer2-1">하단메뉴</div>
                <div class="footer2-2">COPYRIGHT</div>
            </div>
        </footer>
    </div>
</body>

</html>
```

---

### CSS

```css
* {
    font-family: "nanumSquareNeo";
    text-align: center;
    margin: 0;
    padding: 0;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#wrap {
    width: 100%;
}

#header {
    width: 1340px;
    margin: 0 auto;
    display: flex;
}

#header .logo {
    width: 20%;
    height: 100px;
    background-color: #efefef;
}

#header .nav {
    width: 80%;
    height: 100px;
    background-color: #e3e3e3;
}

#slider {
    width: 100%;
    height: 350px;
    background-color: #d9d9d9;
    position: relative;
}

#slider .link {
    width: 1340px;
    height: 100px;
    background-color: #d1d1d1;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translateX(-50%);
}

#contents {
    width: 1340px;
    margin: 0 auto;
}

#contents .banner {
    width: 100%;
    height: 150px;
    background-color: #c7c7c7;
}

#contents .notice {
    width: 100%;
    height: 300px;
    background-color: #bbbbbb;
}

#footer {
    width: 1340px;
    height: 120px;
    margin: 0 auto;
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 120px;
    background-color: #b8b8b8;
}

#footer .footer2 {
    width: 80%;
    height: 120px;
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 60px;
    background-color: #b1b1b1;
}

#footer .footer2 .footer2-2 {
    width: 100%;
    height: 60px;
    background-color: #a3a3a3;
}

.logo,
.nav,
.link,
.banner,
.notice,
.footer1,
.footer2-1,
.footer2-2,
#slider {
    display: flex;
    align-items: center;
    justify-content: center;
}

#contents {
    line-height: 400px;
}
```
