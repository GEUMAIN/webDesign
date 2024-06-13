### 7일차

### 레이아웃 D형

---

## 레이아웃 D-4

---

![깃헙1.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/46f5c52a-3d08-42d1-af9e-60cacc97f637/%EA%B9%83%ED%97%991.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 D-4</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">

        <aside id="aside">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </aside>

        <main id="main">

            <article id="slider">이미지 슬라이드</article>
            <article id="link">링크</article>

            <section id="contents">
                <div class="content1">공지사항</div>
                <div class="content2">갤러리</div>
            </section>
        </main>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">
                <div class="footer2-1">하단메뉴</div>
                <div class="footer2-2">COPYRIGHT</div>
            </div>
            <div class="footer3">패밀리 사이트</div>
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
    display: flex;
    flex-wrap: wrap;
}

#aside {
    width: 200px;
}

#aside .logo {
    width: 100%;
    height: 100px;
    background-color: #efefef;
}

#aside .nav {
    width: 100%;
    height: 700px;
    background-color: #e3e3e3;
}

#main {
    width: calc(100% - 200px);
}

#slider {
    width: 100%;
    height: 400px;
    background-color: #d9d9d9;
}

#link {
    width: 100%;
    height: 150px;
    background-color: #d1d1d1;
}

#contents {
    width: 100%;
    display: flex;
}

#contents .content1 {
    width: 50%;
    height: 250px;
    background-color: #c7c7c7;
}

#contents .content2 {
    width: 50%;
    height: 250px;
    background-color: #bababa;
}

#footer {
    width: 100%;
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 100px;
    background-color: #c7c7c7;
}

#footer .footer2 {
    width: 60%;
    height: 100px;
}

.footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #bcbcbc;
}

.footer2 .footer2-2 {
    width: 100%;
    height: 50px;
    background-color: #b1b1b1;
}

#footer .footer3 {
    width: 20%;
    height: 100px;
    background-color: #a3a3a3;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#aside h1,
.footer1,
.footer2,
.footer3 {
    line-height: 100px;
}

#aside nav {
    line-height: 550px;
}

.footer2 .footer2-1,
.footer2 .footer2-2 {
    line-height: 50px;
}

#slider {
    line-height: 400px;
}

#link {
    line-height: 150px;
}

#banner {
    line-height: 200px;
}

#contents {
    line-height: 250px;
}
```

---

### 레이아웃 E형

## 레이아웃 E-1

---

![깃헙2.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/50c26059-c2de-4b26-9538-ebea8fbd14cb/%EA%B9%83%ED%97%992.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 E-1</title>
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

#main {
    width: 100%;
    height: calc(100vh - 200px);
    display: flex;
}

#header {
    width: 200px;
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
}

#footer .footer1 {
    width: 20%;
    height: 120px;
    background-color: #a3a3a3;
}

#footer .footer2 {
    width: 80%;
}

.footer2 .footer2-1 {
    width: 100%;
    height: 60px;
    background-color: #9d9d9d;
}

.footer2 .footer2-2 {
    width: 100%;
    height: 60px;
    background-color: #808080;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

.logo,
.nav,
.banner,
.gallery,
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
```

---

## 레이아웃 E-2

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 E-2</title>
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
            <section id="contetns">
                <article class="notice">공지사항</article>
                <artcle class="gallery">갤러리</artcle>
                <article class="link">링크</article>
            </section>
            <article id="slider">이미지 슬라이드</article>
        </main>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">COPYRIGHT</div>
            <div class="footer3">패밀리사이트</div>
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
    width: 100%;
    display: flex;
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

#contents {
    width: 400px;
}

#contents .notice {
    width: 100%;
    height: 300px;
    background-color: #d9d9d9;
}

#contents .gallery {
    width: 100%;
    height: 300px;
    background-color: #d1d1d1;
}

#contents .link {
    width: 100%;
    height: 300px;
    background-color: #c7c7c7;
}

#slider {
    width: calc(100% - 600px);
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

h1 {
    font-size: 16px;
    font-weight: normal;
}

.logo,
.nav,
.notice,
.gallery,
.link,
.footer1,
.footer2,
.footer3,
#slider {
    display: flex;
    align-items: center;
    justify-content: center;
}
```
