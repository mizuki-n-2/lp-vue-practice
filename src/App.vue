<template>
  <div id="app">
    <Header></Header>
    <main>
      <!-- eyecatch -->
      <div id="eyecatch">
        <p class="eyecatch-msg">機械ではできない仕事を</p>
        <div class="news-container flex">
          <div class="news-item news-content">
            <p class="news-date text">2019/01/01</p>
            <p class="news-text text">ニュースタイトルがここには入ります。3月の決算報告書</p>
          </div>
          <div class="news-item news text">
            <p>news</p>
          </div>
        </div>
      </div>
      <!-- about -->
      <div id="about">
        <div class="about-content">
          <h2 class="about-title">お客様のために進化する成長企業であり続ける</h2>
          <p class="text about-text">顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
          <a href="" class="btn about__btn">ミッション詳細</a>
        </div>
        <img src="./assets/mission-img.jpg" class="about__img">
      </div>
      <!-- service -->
      <div id="service">
        <h2 class="section-title">service</h2>
        <div class="flex service-content service-content-right">
          <img src="./assets/service2.jpg" class="service__img">
          <div class="business business-right">
            <h5 class="text">Web制作事業</h5>
            <p class="text business-subtitle">コーチングのミッション</p>
            <p class="text">ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設者から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります</p>
            <div class="service__btn-container">
              <a href="" class="btn service__btn">サービス詳細</a>
            </div>
          </div>
        </div>
        <div class="flex service-content">
          <img src="./assets/service1.jpg" class="service__img">
          <div class="business business-left">
            <h5 class="text">Web制作事業</h5>
            <p class="text business-subtitle">コーチングのミッション</p>
            <p class="text">ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設者から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります</p>
            <div class="service__btn-container">
              <a href="" class="btn service__btn">サービス詳細</a>
            </div>
          </div>
        </div>
      </div>
      <!-- info -->
      <div class="flex between" id="info">
        <div class="info-content company">
          <h2 class="section-title">company</h2>
          <p class="sub-section-title">会社概要</p>
        </div>
        <div class="info-content recruit">
          <h2 class="section-title">recruit</h2>
          <p class="sub-section-title">採用情報</p>
        </div>
      </div>
      <!-- faq -->
      <div class="faq wrap">
        <table>
          <tr>
            <th>FAQ</th>
            <td class="text">良くある質問</td>
          </tr>
        </table>
      </div>
      <!-- contact -->
      <div id="contact">
        <h2 class="section-title">contact</h2>
        <p class="sub-section-title">お問い合わせ</p>
        <div class="contact-container">
          <p class="msg">お気軽にお問い合わせください。</p>
          <p class="text">資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力ホームにご記入お願いいたします。</p>
          <a href="" class="btn contact__btn">お問い合わせへ</a>
        </div>
      </div>
    </main>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}

/* 共通のスタイル */
.section-title {
  font-size: 30px;
  font-weight: bold;
  margin: 10px 0;
  text-align: center;
}

img {
  display: block;
  width: 100%;
}

.wrap {
  width: 80%;
  margin: 0 auto 50px;
}

.flex {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.between {
  justify-content: space-between;
}

a {
  text-decoration: none;
}

.btn {
  font-size: 12px;
  border-radius: 1px;
  padding: 8px 25px;
  border: 1px solid;
  display: inline-block;
}

.text {
  font-size: 12px;
  line-height: 1.5em;
}

.logo {
  color: #f2f2f2;
  padding-left: 20px;
}

.nav__list {
  color: #f2f2f2;
  font-size: 12px;
  padding: 0 20px;
}

/* ここからその他のスタイル */
/* eyecatch */
#eyecatch {
  height: 600px;
  background: url(./assets/eyecatch.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

.eyecatch-msg {
  color: #f2f2f2;
  font-size: 40px;
  font-weight: bold;
  font-family: "ＭＳ ゴシック", sans-serif;
  font-style: italic;
  position: absolute;
  top: 58%;
  left: 10%;
}

.news-container {
  width: 50%;
  position: absolute;
  right: 0;
  bottom: 0;
  font-size: 12px;
}

.news-item {
  height: 50px;
}

.news-content {
  width: 75%;
  background: #f2f2f2;
}

.news-date {
  padding: 0 3px; 
}

.news-text {
  padding: 0 10px;
}

.news {
  width: 25%;
  background: #000;
  color: #f2f2f2;
  line-height: 50px;
  text-align: center;
}

/* about */
#about {
  background: #000;
  height: 360px;
  position: relative;
}

.about__img {
  width: 40%;
  height: 85%;
  position: absolute;
  top: 25%;
  right: 5%;
}

.about-content {
  width: 57%;
  color: #f2f2f2;
  position: absolute;
  top: 50%;
  left: 45%;
  transform: translate(-50%,-50%);
  z-index: 10;
  margin: 20px 0;
}

.about-title {
  font-size: 20px;
  font-weight: bold;
}

.about-text {
  padding: 25px 0;
}

.about__btn {
  color: #000;
  font-weight: bold;
  background: #f2f2f2;
  border-color: #f2f2f2;
}

/* service */
#service {
  height: 1120px;
  margin-top: 100px;
  background: #ddd;
}

#service .section-title {
  padding-top: 20px;
}

.business {
  width: 45%;
  height: 250px;
  background: #f2f2f2;
  box-sizing: border-box;
  padding: 65px;
  font-size: 12px;
  position: absolute;
}

.business-subtitle {
  padding: 12px 0;
}

.service__btn {
  color: #000;
  border-color: #000;
}

.service__btn-container {
  text-align: right;
  padding: 10px 0;
}

.service__img {
  width: 50%;
}

.service-content {
  margin-bottom: 150px;
  position: relative;
}

.service-content-right {
  justify-content: flex-end;
}

.business-right {
  left: 15%;
}

.business-left {
  top: 23%;
  left: 40%;
}

/* info */
#info {
  padding: 100px 0;
}

.info-content {
  color: #f2f2f2;
  width: 48%;
  height: 200px;
  text-align: center;
}

#info .section-title {
  padding-top: 60px;
}

.sub-section-title {
  font-weight: bold;
}

.company {
  background: url(./assets/company.jpeg) no-repeat;
  background-size: cover;
  background-position: center;
}

.recruit {
  background: url(./assets/recruit.jpg) no-repeat;
  background-size: cover;
  background-position: center;
}

/* faq */
.faq {
  background: #000;
  color: #f2f2f2;
  height: 80px;
  line-height: 80px;
  margin-bottom: 100px;
  position: relative;
}

.faq td {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
}

.faq th {
  font-size: 24px;
  font-family: Arial, Helvetica, sans-serif;
}

.faq table {
  width: 95%;
  margin: 0 auto;
  text-align: left;
}

/* contact */
#contact {
  height: 250px;
  background: url(./assets/contact-bg.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  color: #f2f2f2;
  text-align: center;
  padding: 150px 0;
}

.msg {
  font-size: 24px;
  padding: 30px 0;
}

.contact__btn {
  color: #f2f2f2;
  border-color: #f2f2f2;
  margin: 30px 0;
}

/* レスポンシブ */
@media screen and (max-width: 768px) {
  /* font-size */
  .text,
  .right {
    font-size: 1rem;
  }

  .section-title {
    font-size: 3rem;
  }

  .logo,
  .sub-section-title {
    font-size: 1.2rem;
  }

  .about-title {
    font-size: 2.2rem;
    line-height: 1.5em;
  }

  .btn {
    font-size: 1rem;
    padding: 12px 35px;
  }

  .msg {
    font-size: 2.8rem;
    padding: 50px 0;
  }

  /* eyecatch */ 
  .eyecatch-msg {
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    font-size: 4rem;
    width: 80%;
    text-align: center;
  }

  .news-container {
    width: 100%;
  }

  /* about */
  #about {
    height: 470px;
  }
  .about-content {
    width: 75%;
    left: 50%;
  }

  .about__img {
    width: 35%;
    height: auto;
    top: 75%;
    right: 10%;
  }

  /* service */ 
  #service {
    height: 1520px;
    margin-top: 40px;
  }

  .service__img {
    width: 90%;
    margin: 0 auto;
  }

  .business {
    width: 90%;
    top: 100%;
    left: 5%;
    padding: 30px 50px;
  }

  .service-content:nth-of-type(2) {
    top: 10%;
  }

  /* info */
  #info {
    padding: 50px 0;
  }

  .info-content {
    width: 100%;
  }

  /* faq */ 
  .faq {
    width: 95%;
    height: 120px;
    line-height: 120px;
    margin-bottom: 50px;
  }

  .faq table {
    width: 80%;
  }

  /* contact */
  #contact {
    height: 300px;
  }

  .contact-container {
    width: 80%;
    margin: 0 auto;
  }
}

/* モバイル */
@media screen and (max-width: 480px) {
  /* eyecatch */
  .news-item {
    height: 80px;
  }

  .news {
    line-height: 80px;
  }

  .news-text {
    padding: 0 20px;
  }

  /* about */
  #about {
    height: 530px;
  }

  .about__img {
    width: 40%;
    top: 89%;
    right: 6%;
  }

  /* service */
  #service {
    height: 1200px;
  }

  .service-content:nth-of-type(2) {
    top: 12%;
  }

  .business {
    padding: 20px 40px;
    height: 300px;
  }

  .service-content:nth-of-type(2) {
    top: 15%;
  }

  /* contact */
  #contact {
    height: 400px;
  }
}

@media screen and (max-width: 320px) {
  /* eyecatch */
  .news-item {
    height: 100px;
  }

  .news {
    line-height: 100px;
  }

  /* about */ 
  #about {
    height: 600px;
  }

  .about__img {
    top: 95%;
  }

  /* service */
  #service {
    height: 1100px;
  }
}
</style>
