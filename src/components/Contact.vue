<template>
  <div id="contact">
    <h2 class="section-title">contact</h2>
    <p class="sub-section-title">お問い合わせ</p>
    <div class="contact-container">
      <p class="contact-msg">お気軽にお問い合わせください。</p>
      <p class="text">資料請求・お問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡もお問い合わせページに飛んでいただいて、入力ホームにご記入お願いいたします。</p>
      <a href="" class="btn contact__btn">お問い合わせへ</a>
    </div>
  </div>
</template>

<style scoped>
#contact {
  height: 250px;
  background: url(../assets/contact-bg.jpg) no-repeat;
  background-size: cover;
  background-position: center;
  color: #f2f2f2;
  text-align: center;
  padding: 150px 0;
}

.contact-msg {
  font-size: 24px;
  padding: 30px 0;
}

.contact__btn {
  color: #f2f2f2;
  border-color: #f2f2f2;
  margin: 30px 0;
}

@media screen and (max-width: 768px) {
  #contact {
    height: 300px;
  }

  .contact-container {
    width: 80%;
    margin: 0 auto;
  }

  .contact-msg {
    font-size: 2.8rem;
    padding: 50px 0;
  }
}

@media screen and (max-width: 480px) {
  #contact {
    height: 400px;
  }
}
</style>