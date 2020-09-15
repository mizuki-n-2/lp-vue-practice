<template>
  <div id="app">
    <Header></Header>
    <Eyecatch></Eyecatch> 
    <About></About>
    <Service></Service>
    <Info></Info>
    <Faq></Faq>
    <Contact></Contact>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Eyecatch from "./components/Eyecatch";
import About from "./components/About";
import Service from "./components/Service";
import Info from "./components/Info";
import Faq from "./components/Faq";
import Contact from "./components/Contact";
import Footer from "./components/Footer";
export default {
  components: {
    Header,
    Eyecatch,
    About,
    Service,
    Info,
    Faq,
    Contact,
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
/* レスポンシブ */
@media screen and (max-width: 768px) {
  .text {
    font-size: 1rem;
  }

  .section-title {
    font-size: 3rem;
  }

  .logo,
  .sub-section-title {
    font-size: 1.2rem;
  }

  .btn {
    font-size: 1rem;
    padding: 12px 35px;
  }
}
</style>
