### 4일차

### 레이아웃 B형

## 레이아웃 B-4

---

![깃헙1](https://github.com/GEUMAIN/webDesign/assets/128437656/0ed985e5-e330-4b8a-a8c7-397234049019)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 B-4</title>
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
                <section class="content1">공지사항</section>
                <section class="content2">갤러리</section>
                <section class="content3">배너</section>
            </div>
        </main>

        <footer id="footer">
            <div class="container">
                <div class="footer1">
                    <div class="footer1-1">하단 메뉴</div>
                    <div class="footer1-2">COPYRIGHT</div>
                </div>
                <div class="footer2">패밀리 사이트</div>
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
    background-color: #d1d1d1;
}

#footer .footer1 {
    width: 80%;
}

#footer .footer1 .footer1-1 {
    width: 100%;
    height: 50px;
    background-color: #9d9d9d;
}

#footer .footer1 .footer1-2 {
    width: 100%;
    height: 50px;
    background-color: #929292;
}

#footer .footer2 {
    width: 20%;
    height: 100px;
    background-color: #838383;
}

.container {
    width: 1200px;
    height: inherit;
    margin: 0 auto;
    background-color: rgba(0, 0, 0, 0.2);
    display: flex;
}

.logo,
.nav,
.footer1,
.footer2 {
    line-height: 100px;
}

.footer1-1,
.footer1-2 {
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

.container {
    justify-content: center;
}
```

---

---

### 레이아웃 C형

## 레이아웃 C-1

---

![깃헙2](https://github.com/GEUMAIN/webDesign/assets/128437656/9e0c43eb-e190-4a87-8ea4-01a784c625a1)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
    <title>Document</title>

</head>

<body>
    <div id="wrap">
        <aside id="aside">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </aside>

        <main id="main">
            <article id="slider">이미지 슬라이드
            </article>

            <section id="contents">
                <article class="content1">공지사항/갤러리</article>
                <article class="content2">배너</article>
                <article class="content3">바로가기</article>
            </section>

            <footer id="footer">
                <div class="footer1">로고</div>
                <div class="footer2">
                    <div class="footer2-1">하단 메뉴</div>
                    <div class="footer2-2">COPYRIGHT</div>
                </div>
            </footer>
        </main>
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
    width: 1000px;
    display: flex;
}

#aside {
    width: 20%;
}

#aside .logo {
    width: 100%;
    height: 100px;
    background-color: #efefef;
}

#aside .nav {
    width: 100%;
    height: 550px;
    background-color: #d9d9d9;
}

#main {
    width: 80%;
    height: 550px;
    background-color: #e3e3e3;
}

#slider {
    width: 100%;
    height: 350px;
    background-color: #c7c7c7;
}

#contents {
    width: 100%;
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
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 100px;
    background-color: #9d9d9d;
}

#footer .footer2 {
    width: 80%;
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #929292;
}

#footer .footer2 .footer2-2 {
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
.footer2 {
    line-height: 100px;
}

.nav {
    line-height: 550px;
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

.container {
    justify-content: center;
}
```
