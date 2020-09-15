<template>
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
</template>

<style scoped>
#eyecatch {
  height: 600px;
  background: url(../assets/eyecatch.jpg) no-repeat;
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

@media screen and (max-width: 768px) {
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
}

@media screen and (max-width: 480px) {
  .news-item {
    height: 80px;
  }

  .news {
    line-height: 80px;
  }

  .news-text {
    padding: 0 20px;
  }
}

@media screen and (max-width: 320px) {
  .news-item {
    height: 100px;
  }

  .news {
    line-height: 100px;
  }
}
</style>