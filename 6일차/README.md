### 6일차

### 레이아웃 D형

## 레이아웃 D-2

---

![깃헙6.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/031a6771-bb4d-49d5-a8e6-66088a5a9650/%EA%B9%83%ED%97%996.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 D-2</title>
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
            <article id="slider">
                <div class="image">이미지 슬라이드</div>
                <div class="banner">배너</div>
            </article>

            <section id="contents">
                <div class="content1">공지사항</div>
                <div class="content2">갤러리</div>
            </section>
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
    line-height: 100px;
    background-color: #efefef;
}

#aside .nav {
    line-height: 550px;
    background-color: #e3e3e3;
}

#main {
    width: calc(100% - 200px);
}

#slider {
    width: 100%;
    display: flex;
}

#slider .image {
    width: calc(100% - 230px);
    height: 400px;
    background-color: #d9d9d9;
}

#slider .banner {
    width: 230px;
    height: 400px;
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
    background-color: #bcbcbc;
}

#footer {
    width: 100%;
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 200px;
    background-color: #b1b1b1;
}

#footer .footer2 {
    width: 60%;
    height: 200px;
    background-color: #a3a3a3;
}

#footer .footer3 {
    width: 20%;
    height: 200px;
    background-color: #9d9d9d;
}

h1 {
    font-size: 16px;
    font-weight: normal;
}

#aside h1,
.footer1,
.footer2,
.footer3 {
    line-height: 200px;
}

#aside nav {
    line-height: 550px;
}

#slider {
    line-height: 400px;
}

#contents {
    line-height: 250px;
}
```

---

## 레이아웃 D-3

---

![깃헙7.PNG](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/95be1643-d92f-47ae-a43b-f023ff59e71a/%EA%B9%83%ED%97%997.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 D-3</title>
    <link rel="stylesheet" href="https://websfont.github.io/nanumSquareNeo/nanumSquareNeo.css">
    <link rel="stylesheet" href="CSS/style.css">
</head>

<body>
    <div id="wrap">
        <aside id="aside">
            <h1>로고</h1>
            <nav>메뉴</nav>
        </aside>

        <main id="main">
            <article id="slider">이미지 슬라이드
                <div class="link">링크</div>
            </article>
            <article id="banner">배너</article>
            <section id="contents">공지사항/갤러리</section>
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
    display: flex;
    flex-wrap: wrap;
}

#aside {
    width: 200px;
}

#aside h1 {
    width: 100%;
    height: 100px;
    background-color: #efefef;
}

#aside nav {
    width: 100%;
    height: 750px;
    background-color: #e3e3e3;
}

#main {
    width: calc(100% - 200px);
}

#slider {
    width: 100%;
    height: 400px;
    background-color: #d9d9d9;
    position: relative;
}

#slider .link {
    position: absolute;
    right: 0;
    top: 0;
    width: 100px;
    height: 300px;
    background-color: #9d9d9d;
}

#banner {
    width: 100%;
    height: 200px;
    background-color: #d1d1d1;
}

#contents {
    width: 100%;
    height: 250px;
    background-color: #c7c7c7;
}

#footer {
    width: 100%;
    display: flex;
}

#footer .footer1 {
    width: 20%;
    height: 120px;
    background-color: #bcbcbc;
}

#footer .footer2 {
    width: 80%;
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

#aside h1,
.footer1,
.footer2 {
    line-height: 100px;
}

.footer2-1,
.footer2-2 {
    line-height: 50px;
}

#aside nav {
    line-height: 550px;
}

#slider {
    line-height: 400px;
}

#slider .link {
    line-height: 300px;
}

#banner {
    line-height: 200px;
}

#contents {
    line-height: 250px;
}
```
