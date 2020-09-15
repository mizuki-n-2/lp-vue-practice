<template>
  <footer>
    <div class="flex between">
      <h1 class="logo footer-logo">estra inc.</h1>
      <nav class="footer__nav">
        <ul class="flex">
          <li><a href="#" class="nav__list">home</a></li>
          <li><a href="#about" class="nav__list">about</a></li>
          <li><a href="#service" class="nav__list">service</a></li>
          <li><a href="#info" class="nav__list">company</a></li>
          <li><a href="#info" class="nav__list">price</a></li>
          <li><a href="#contact" class="nav__list">contact</a></li>
        </ul>
      </nav>
    </div>
    <div class="right">
      <small>Copyright 2019 estra inc. All Rights Reserved.</small>
    </div>
  </footer>
</template>

<style scoped>
footer {
  height: 100px;
  line-height: 50px;
  background: #000;
}

.right {
  color: #f2f2f2;
  font-size: 12px;
  text-align: center;
}

@media screen and (max-width: 768px) {
  .footer-logo {
    margin: 0 auto;
  }

  .footer__nav {
    display: none;
  }
}

@media screen and (max-width: 320px) {
  .right {
    font-size: 0.8rem;
  }
}
</style>