<template>
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
</template>

<style scoped>
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
  background: url(../assets/company.jpeg) no-repeat;
  background-size: cover;
  background-position: center;
}

.recruit {
  background: url(../assets/recruit.jpg) no-repeat;
  background-size: cover;
  background-position: center;
}

@media screen and (max-width: 768px) {
  #info {
    padding: 50px 0;
  }

  .info-content {
    width: 100%;
  }
}
</style>