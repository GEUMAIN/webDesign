### 8일차

---

### 레이아웃 E형

## 레이아웃 E-3

---

![깃헙4](https://github.com/GEUMAIN/webDesign/assets/128437656/9a2fce47-9651-47b5-83f3-a91fb6d99a1a)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 E-3</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <main id="main">
            <header id="header">
                <h1 class="logo">로고</h1>
                <nav class="nav">메뉴</nav>
            </header>

            <section id="contents">
                <article class="banner">배너</article>
                <article class="notice">공지사항</article>
                <article class="gallery">갤러리</article>
            </section>

            <article id="slider">이미지 슬라이드</article>
        </main>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">COPYRIGHT</div>
            <div class="footer3">SNS</div>
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
    margin: 0;
    padding: 0;
    text-align: center;
}

#wrap {
    width: 100%;
}

#main {
    width: 100%;
    display: flex;
}

#header {
    width: 200px;
}

#header .logo {
    width: 100%;
    height: 100px;
    background-color: #efefef;
}

#header .nav {
    width: 100%;
    height: 650px;
    background-color: #e3e3e3;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#contents {
    width: 400px;
}

#contents .banner {
    width: 100%;
    height: 150px;
    background-color: #d9d9d9;
}

#contents .notice {
    width: 100%;
    height: 300px;
    background-color: #d1d1d1;
}

#contents .gallery {
    width: 100%;
    height: 300px;
    background-color: #c7c7c7;
}

#slider {
    width: calc(100% - 400px);
    height: 750px;
    background-color: #bcbcbc;
}

#footer {
    width: 100%;
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 100px;
    background-color: #b1b1b1;
}

#footer .footer2 {
    width: 60%;
    height: 100px;
    background-color: #a3a3a3;
}

#footer .footer3 {
    width: 20%;
    height: 100px;
    background-color: #9d9d9d;
}

.logo,
.nav,
.banner,
.notice,
.gallery,
.footer1,
.footer2,
.footer3,
#slider {
    display: flex;
    align-items: center;
    justify-content: center;
}
```

---

## 레이아웃 E-4

---

![깃헙5](https://github.com/GEUMAIN/webDesign/assets/128437656/95ac7b9e-2585-417a-b2a4-a43b494741c6)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 E-4</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <main id="main">
            <header id="header">
                <h1 class="logo">로고</h1>
                <nav class="nav">메뉴</nav>
            </header>

            <section id="contents">
                <article class="banner">배너</article>
                <article class="notice">공지사항</article>
                <article class="gallery">갤러리</article>
                <article class="link">링크</article>
            </section>

            <article id="slider">이미지 슬라이드</article>
        </main>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">
                <div class="footer2-1">하단메뉴</div>
                <div class="footer2-2">COPYRIGHT</div>
            </div>
            <div class="footer3">SNS</div>
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

#main {
    width: 100%;
    height: calc(100vh - 120px);
    display: flex;
}

#header {
    width: 200px;
    height: 100%;
}

#header .logo {
    width: 100%;
    height: 10%;
    background-color: #efefef;
}

#header .nav {
    width: 100%;
    height: 90%;
    background-color: #e3e3e3;
}

#contents {
    width: 400px;
    height: 100%;
}

#contents .banner {
    width: 100%;
    height: 15%;
    background-color: #d9d9d9;
}

#contents .notice {
    width: 100%;
    height: 35%;
    background-color: #d1d1d1;
}

#contents .gallery {
    width: 100%;
    height: 35%;
    background-color: #c7c7c7;
}

#contents .link {
    width: 100%;
    height: 15%;
    background-color: #bcbcbc;
}

#slider {
    width: calc(100% - 600px);
    height: 100%;
    background-color: #b1b1b1;
}

#footer {
    width: 100%;
    display: flex;
    flex-wrap: wrap;
}

#footer .footer1 {
    width: 200px;
    height: 120px;
    background-color: #a3a3a3;
}

#footer .footer2 {
    width: calc(100% - 400px);
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 60px;
    background-color: #9d9d9d;
}

#footer .footer2 .footer2-2 {
    width: 100%;
    height: 60px;
    background-color: #929292;
}

#footer .footer3 {
    width: 200px;
    height: 120px;
    background-color: #838383;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

.logo,
.nav,
.banner,
.notice,
.gallery,
.link,
.footer1,
.footer2-1,
.footer2-2,
.footer3,
#slider {
    display: flex;
    align-items: center;
    justify-content: center;
}
```

---
