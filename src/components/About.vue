<template>
  <div id="about">
    <div class="about-content">
      <h2 class="about-title">お客様のために進化する成長企業であり続ける</h2>
      <p class="text about-text">顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供いたします。</p>
      <a href="" class="btn about__btn">ミッション詳細</a>
    </div>
    <img src="../assets/mission-img.jpg" class="about__img">
  </div>
</template>

<style scoped>
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

@media screen and (max-width: 768px) {
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

  .about-title {
    font-size: 2.2rem;
    line-height: 1.5em;
  }
}

@media screen and (max-width: 480px) {
  #about {
    height: 530px;
  }

  .about__img {
    width: 40%;
    top: 89%;
    right: 6%;
  }
}

@media screen and (max-width: 320px) {
  #about {
    height: 600px;
  }

  .about__img {
    top: 95%;
  }
}
</style>