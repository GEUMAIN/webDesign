### 3일차

### 레이아웃 B형

## 레이아웃 B-2

---

![깃허브6](https://github.com/GEUMAIN/webDesign/assets/128437656/c5bc9c12-f74d-4042-b726-6fd76ba36aee)

---

### HTML

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 B-2</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <header id="header">
            <div class="header_container">
                <h1 class="logo">로고</h1>
                <nav class="nav">메뉴</nav>
            </div>
        </header>

        <article id="slider">이미지 슬라이드</article>

        <main id="contents">
            <section class="content1">공지사항/갤러리</section>
            <section class="content2">배너</section>
            <section class="content3">바로가기</section>
        </main>

        <footer id="footer">
            <div class="footer_container">
                <div class="footer1">COPYRIGHT</div>
                <div class="footer2">
                    <div class="footer2-1">SNS</div>
                    <div class="footer2-2">패밀리 사이트</div>
                </div>
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
    margin: 0;
    padding: 0;
    font-family: "nanumSquareNeo";
    text-align: center;
}

#wrap {
    width: 100%;
}

#header {
    width: 100%;
    background-color: #efefef;
}

#header .header_container {
    width: 1200px;
    margin: 0 auto;
    display: flex;
}

#header .header_container .logo {
    width: 20%;
    height: 100px;
    background-color: #d9d9d9;
}

#header .header_container .nav {
    width: 80%;
    height: 100px;
    background-color: #d1d1d1;
}

#slider {
    width: 1200px;
    height: 300px;
    margin: 0 auto;
    background-color: #c7c7c7;
}

#contents {
    width: 1200px;
    margin: 0 auto;
    display: flex;
}

#contents .content1 {
    width: 33.3333%;
    height: 200px;
    background-color: #bcbcbc;
}

#contents .content2 {
    width: 33.3333%;
    height: 200px;
    background-color: #b1b1b1;
}

#contents .content3 {
    width: 33.3333%;
    height: 200px;
    background-color: #a3a3a3;
}

#footer {
    width: 100%;
    height: 100px;
    background-color: #d1d1d1;
}

#footer .footer_container {
    width: 1200px;
    margin: 0 auto;
    display: flex;
}

#footer .footer_container .footer1 {
    width: 80%;
    height: 100px;
    background-color: #9d9d9d;
}

#footer .footer_container .footer2 {
    width: 20%;
}

#footer .footer_container .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #929292;
}

#footer .footer_container .footer2 .footer2-2 {
    width: 100%;
    height: 50px;
    background-color: #838383;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

.logo,
.nav,
.footer1 {
    line-height: 100px;
}

.footer2-1,
.footer2-2 {
    line-height: 50px;
}

#slider {
    line-height: 300px;
}

.content1,
.content2,
.content3 {
    line-height: 200px;
}
```

---

## 레이아웃 B-3

---

![깃허브7](https://github.com/GEUMAIN/webDesign/assets/128437656/8c5a22ad-3e92-4bc0-acc2-0a05f8859833)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 B-3</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <header id="header">
            <div class="container">
                <h1 class="logo">로고</h1>
                <nav class="nav">메뉴</nav>
            </div>
        </header>

        <article id="slider">
            <div class="container">이미지 슬라이드</div>
        </article>

        <main id="contents">
            <div class="container">
                <div class="content1">공지사항</div>
                <div class="content2">갤러리</div>
                <div class="content3">배너</div>
            </div>
        </main>

        <footer id="footer">
            <div class="container">
                <div class="footer1">로고</div>
                <div class="footer2">COPYRIGHT</div>
                <div class="footer3">SNS</div>
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
    margin: 0;
    padding: 0;
    font-family: "nanumSquareNeo";
    text-align: center;
}

#wrap {
    width: 100%;
}

#header {
    width: 100%;
    height: 100px;
    background-color: #efefef;
}

#header .logo {
    width: 20%;
    height: 100px;
    background-color: #c7c7c7;
}

#header .nav {
    width: 80%;
    height: 100px;
    background-color: #bcbcbc;
}

#slider {
    width: 100%;
    height: 300px;
}

#contents {
    width: 100%;
}

#contents .content1 {
    width: 33.3333%;
    height: 200px;
    background-color: #bcbcbc;
}

#contents .content2 {
    width: 33.3333%;
    height: 200px;
    background-color: #b1b1b1;
}

#contents .content3 {
    width: 33.3333%;
    height: 200px;
    background-color: #a3a3a3;
}

#footer {
    width: 100%;
    height: 100px;
    background-color: #d1d1d1;
}

#footer .footer_container {
    width: 1200px;
    margin: 0 auto;
    display: flex;
}

#footer .footer_container .footer1 {
    width: 80%;
    height: 100px;
    background-color: #9d9d9d;
}

#footer .footer_container .footer2 {
    width: 20%;
}

#footer .footer_container .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #929292;
}

#footer .footer_container .footer2 .footer2-2 {
    width: 100%;
    height: 50px;
    background-color: #838383;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

.logo,
.nav,
.footer1,
.footer2,
.footer3 {
    line-height: 100px;
}

#slider {
    line-height: 300px;
}

.content1,
.content2,
.content3 {
    line-height: 200px;
}

.container {
    justify-content: center;
    width: 1200px;
    height: inherit;
    margin: 0 auto;
    background-color: rgba(0, 0, 0, 0.2);
    display: flex;
}
```
