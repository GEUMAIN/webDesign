### 2일차

### 레이아웃 A형

## 레이아웃 A-3

---

![깃허브3](https://github.com/GEUMAIN/webDesign/assets/128437656/14d9be02-3119-4df3-8943-ede608fa75de)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 A-3</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <header id="header">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </header>

        <article id="slider">이미지 슬라이드</article>

        <main id="contents">
            <section class="content1">공지사항/갤러리</section>
            <section class="content2">배너</section>
            <section class="content3">바로가기</section>
        </main>

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
    margin: 0;
    padding: 0;
    font-family: "nanumSquareNeo";
    text-align: center;
}

#wrap {
    width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#header {
    width: 100%;
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

#header .logo,
#header .nav,
#footer .footer1 {
    line-height: 100px;
}

#slider {
    width: 100%;
    height: 300px;
    background-color: #d9d9d9;
}

#contents {
    width: 100%;
    display: flex;
}

#contents .content1 {
    width: 33.3333%;
    height: 200px;
    background-color: #d1d1d1;
}

#contents .content2 {
    width: 33.3333%;
    height: 200px;
    background-color: #c7c7c7;
}

#contents .content3 {
    width: 33.3333%;
    height: 200px;
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
    width: 80%;
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #a3a3a3;
}

#footer .footer2 .footer2-2 {
    width: 100%;
    height: 50px;
    background-color: #9d9d9d;
}

#footer .footer2 {
    line-height: 50px;
}

#slider {
    line-height: 300px;
}

#contents .content1,
#contents .content2,
#contents .content3 {
    line-height: 200px;
}
```

---

## 레이아웃 A-4

---

![깃허브4](https://github.com/GEUMAIN/webDesign/assets/128437656/5ef89ba5-bf4b-44fe-97bc-9116119698fa)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 A-4</title>
    <link rel="stylesheet" href="CSS/style.css">
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">

</head>

<body>
    <div id="wrap">
        <header id="header">
            <h1 class="logo">로고</h1>
            <nav class="nav">메뉴</nav>
        </header>

        <article id="slider">이미지 슬라이드</article>

        <main id="contents">
            <section class="content1">공지사항</section>
            <section class="content2">갤러리</section>
            <section class="content3">바로가기</section>
        </main>

        <footer id="footer">
            <div class="footer1">
                <div class="footer1-1">하단메뉴</div>
                <div class="footer1-2">COPYRIGHT</div>
            </div>
            <div class="footer2">패밀리사이트</div>
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
    width: 1200px;
    margin: 0 auto;
}

#header {
    width: 100%;
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
    height: 300px;
    background-color: #d9d9d9;
}

#contents {
    width: 100%;
    display: flex;
}

#contents .content1 {
    width: 33.3333%;
    height: 200x;
    background-color: #d1d1d1;
}

#contents .content2 {
    width: 33.3333%;
    height: 200x;
    background-color: #c7c7c7;
}

#contents .content3 {
    width: 33.3333%;
    height: 200x;
    background-color: #bcbcbc;
}

#footer {
    width: 100%;
    display: flex;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#footer .footer1 .footer1-1 {
    width: 100%;
    height: 50px;
    background-color: #b1b1b1;
}

#footer .footer1 {
    width: 80%;
}

#footer .footer1 .footer1-2 {
    width: 100%;
    height: 50px;
    background-color: #a3a3a3;
}

#footer .footer2 {
    width: 20%;
    height: 100px;
    background-color: #9d9d9d;
}

#header .logo,
#header .nav,
#footer .footer2 {
    line-height: 100px;
}

#footer .footer1-1,
#footer .footer1-2 {
    line-height: 50px;
}

#slider {
    line-height: 300px;
}

#contents .content1,
#contents .content2,
#contents .content3 {
    line-height: 200px;
}
```

---

### 레이아웃 B형

## 레이아웃 B-1

---


![깃허브5](https://github.com/GEUMAIN/webDesign/assets/128437656/2f42ac12-529e-4eb0-863e-deec4949edfc)


---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 B-1</title>
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

        <article id="slider">이미지 슬라이드
        </article>

        <main id="contents">
            <section class="content1">공지사항/갤러리</section>
            <section class="content2">배너</section>
            <section class="content3">바로가기</section>
        </main>

        <footer id="footer">
            <div class="footer__container">
                <div class="footer1">로고</div>
                <div class="footer2">
                    <div class="footer2-1">하단 메뉴</div>
                    <div class="footer2-2">COPYRIGHT</div>
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
    background-color: #d1d1d1;
}

#footer .footer__container {
    width: 1200px;
    margin: 0 auto;
    display: flex;
}

#footer .footer__container .footer1 {
    width: 20%;
    height: 100px;
    background-color: #9d9d9d;
}

#footer .footer__container .footer2 {
    width: 80%;
}

#footer .footer__container .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #929292;
}

#footer .footer__container .footer2 .footer2-2 {
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
}s
```
