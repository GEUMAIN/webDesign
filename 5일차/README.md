### 5일차

### 레이아웃 C형

## 레이아웃 C-2

---

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/ba0c6778-5fd1-417a-91cd-967a17f52f23/Untitled.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 C-2</title>
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
            </article>

            <section id="contents">
                <article class="content1">공지사항</article>
                <article class="content2">갤러러</article>
                <article class="content3">바로가기</article>
            </section>
            <footer id="footer">
                <div class="footer1">COPYRIGHT</div>
                <div class="footer2">
                    <div class="footer2-1">SNS</div>
                    <div class="footer2-2">패밀리 사이트</div>
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

#aside h1 {
    width: 100%;
    height: 100px;
    background-color: #d9d9d9;
}

#aside nav {
    width: 100%;
    height: 550px;
    background-color: #d1d1d1;
}

#main {
    width: 80%;
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
    width: 80%;
    background-color: #838383;
}

#footer .footer2 {
    width: 20%;
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #9d9d9d;
}

#footer .footer2 .footer2-2 {
    width: 100%;
    height: 50px;
    background-color: #929292;
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

#aside nav {
    line-height: 550px;
}

.footer2-1,
.footer2-2 {
    line-height: 50px;
}

#slider {
    line-height: 350px;
}

.content1,
.content2,
.content3 {
    line-height: 200px;
}
```

---

## 레이아웃 C-3

---

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/7d3f169b-8037-4cf7-ac85-f01f13a55c06/Untitled.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 C-3</title>
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
            <section id="contents">
                <article class="content1">공지사항</article>
                <article class="content2">갤러리</article>
                <article class="content3">배너</article>
            </section>

            <footer id="footer">
                <div class="footer1">로고</div>
                <div class="footer2">
                    <div class="footer2-1">하단메뉴</div>
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

#aside h1 {
    width: 100%;
    height: 1100px;
    background-color: #d9d9d9;
}

#aside nav {
    width: 100%;
    height: 550px;
    background-color: #d1d1d1;
}

#main {
    width: 80%;
}

#slider {
    width: 100%;
    height: 300px;
    background-color: #c7c7c7;
}

#contents {
    width: 100%;
    display: flex;
}

#conetnts .content1 {
    width: 33.3333%;
    height: 200px;
    background-color: #bcbcbc;
}

#conetnts .content2 {
    width: 33.3333%;
    height: 200px;
    background-color: #b1b1b1;
}

#conetnts .content3 {
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
    background-color: #838383;
}

#footer .footer2 {
    width: 80%;
}

#footer .footer2 .footer2-1 {
    width: 100%;
    height: 50px;
    background-color: #9d9d9d;
}

#footer .footer2 .footer2-2 {
    width: 100%;
    height: 50px;
    background-color: #929292;
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

#aside nav {
    line-height: 550px;
}

.footer2-1,
.footer2-2 {
    line-height: 200px;
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

## 레이아웃 C-4

---

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/04e260eb-cc74-417a-8cc7-2d133186ffb2/Untitled.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 C-4</title>
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
            <section id="contents">
                <article class="content1">공지사항</article>
                <article class="content2">갤러리</article>
                <article class="content3">바로가기</article>
            </section>
            <footer id="footer">
                <div class="footer1">로고</div>
                <div class="footer2">COPYRIGHT</div>
                <div class="footer3">패밀리사이트</div>
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

#aside h1 {
    width: 100%;
    height: 100px;
    background-color: #d9d9d9;
}

#aside nav {
    width: 100%;
    height: 500px;
    background-color: #d1d1d1;
}

#main {
    width: 80%;
}

#slider {
    width: 100%;
    height: 300px;
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
    width: 60%;
    height: 100px;
    background-color: #929292;
}

#footer .footer3 {
    width: 20%;
    height: 100px;
    background-color: #838383;
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
    line-height: 500px;
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

### 레이아웃 D형

---

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/fa97d740-13f6-4ddc-9939-b86bb2c976d6/66405dce-a1ca-4fa9-a11a-9a58703aec79/Untitled.png)

---

### HTML

```html
<!DOCTYPE html>
<html lang="ko">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>웹디자인기능사 레이아웃 D-1</title>
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
            <article id="slider">이미지 슬라이드
                <div class="link">링크</div>
            </article>
            <article id="banner">배너</article>
            <section id="contents">공지사항/갤러리</section>
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
    height: 750px;
    background-color: #e3e3e3;
}

#main {
    width: calc(100% - 200px);
    height: 850px;
    background-color: #e3e3e3;
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
    height: 100px;
    background-color: #bcbcbc;
}

#footer .footer2 {
    width: 60%;
    height: 100px;
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
    line-height: 500px;
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
