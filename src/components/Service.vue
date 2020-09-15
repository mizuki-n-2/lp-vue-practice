<template>
  <div id="service">
    <h2 class="section-title">service</h2>
    <div class="flex service-content service-content-right">
      <img src="../assets/service2.jpg" class="service__img">
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
      <img src="../assets/service1.jpg" class="service__img">
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
</template>

<style scoped>
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

@media screen and (max-width: 768px) {
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
}

@media screen and (max-width: 480px) {
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
}

@media screen and (max-width: 320px) {
  #service {
    height: 1100px;
  }
}
</style>