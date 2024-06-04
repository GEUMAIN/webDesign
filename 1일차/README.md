### 1일차

### 레이아웃 A형

---

## 레이아웃 A-1

---

![깃허브1](https://github.com/GEUMAIN/webDesign/assets/128437656/c3ae8c70-e5fd-4c60-b5c9-6871c78054a5)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 A-1</title>
    <link rel="stylesheet" href="CSS/style.css?abc">
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
</head>

<body>

    <div id="wrap">
        <!-- 헤더 영역 -->
        <div id="header">
            <div class="logo">로고</div>
            <div class="nav">메뉴</div>
        </div>

        <!-- 슬라이드 영역 -->
        <div id="slider">이미지 슬라이드</div>

        <!-- 콘텐츠 영역 -->
        <div id="contents">
            <div class="content1">공지사항/갤러리</div>
            <div class="content2">배너</div>
            <div class="content3">바로가기</div>
        </div>

        <!-- 푸터 영역 -->
        <div id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">COPYRIGHT</div>
            <div class="footer3">SNS</div>
        </div>
    </div>
</body>

</html>
```

---

### CSS

---

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
    background-color: #d1d1d1;
}

#contents .content2 {
    background-color: #c7c7c7;
}

#contents .content3 {
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

#header .logo,
#header .nav,
#footer .footer1,
#footer .footer2,
#footer .footer3 {
    line-height: 100px;
}

#slider {
    line-height: 300px;
}

#contents .content1,
#contents .content2,
#contents .content3 {
    line-height: 200px;
    width: 33.3333%;
    height: 200px;
}
```

---

## 레이아웃 A-2

---

![깃허브2](https://github.com/GEUMAIN/webDesign/assets/128437656/5ca2bded-2f41-4356-b944-53f6f5460b50)


### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="CSS/style.css?abc">
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
            <section class="content3">배너</section>
        </main>

        <footer id="footer">
            <div class="footer1">로고</div>
            <div class="footer2">COPYRIGHT</div>
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
    margin: 0;
    padding: 0;
    font-family: "nanumSquareNeo";
    text-align: center;
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

#contents .content1,
#contents .content2,
#contents .content3 {
    width: 33.3333%;
    height: 200px;
}

#contents .content1 {
    background-color: #d1d1d1;
}

#contents .content2 {
    background-color: #c7c7c7;
}

#contents .content3 {
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

#header .logo,
#header .nav,
#footer .footer1,
#footer .footer2,
#footer .footer3 {
    line-height: 100px;
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
