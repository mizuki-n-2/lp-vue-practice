<template>
  <header>
    <div class="flex between">
      <h1 class="logo">estra inc.</h1>
      <nav class="header__nav">
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
    <!-- hamburger -->
    <div id="hamburger" @click="hamburger()" :class="{active:isClass}">
      <span></span>
      <span></span>
      <span></span>
    </div>
    <!-- menu -->
    <nav class="menu" :class="{open:isClass}">
      <div class="menu-container">
        <p class="menu-logo">estra inc.</p>
        <ul class="menu-content">
          <li><a href="#" @click="closeMenu()">home</a></li>
          <li><a href="#about" @click="closeMenu()">about</a></li>
          <li><a href="#service" @click="closeMenu()">service</a></li>
          <li><a href="#info" @click="closeMenu()">company</a></li>
          <li><a href="#info" @click="closeMenu()">price</a></li>
          <li><a href="#contact" @click="closeMenu()">contact</a></li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  data() {
    return {
      isClass: false
    };
  },
  methods: {
    hamburger() {
      this.isClass = !this.isClass;
    },
    closeMenu() {
      this.isClass = false;
    }
  }
};
</script>

<style scoped>
header {
  height: 50px;
  background: #000;
  line-height: 50px;
}

@media screen and (max-width: 768px) {
  #hamburger {
    width: 40px;
    height: 40px;
    position: absolute;
    top: 5px;
    right: 10px;
    cursor: pointer;
  }

  #hamburger span {
    width: 35px;
    height: 2px;
    background-color: #fff;
    position: absolute;
  }

  #hamburger span:nth-of-type(1) {
    top: 10px;
  }

  #hamburger span:nth-of-type(2) {
    top: 20px;
  }

  #hamburger span:nth-of-type(3) {
    top: 30px;
  }

  .header__nav {
    display: none;
  }

  #hamburger.active span {
    position: fixed;
    z-index: 200;
    background: #000;
  }

  #hamburger.active span:nth-of-type(1) {
    top: 20px;
    transform: rotate(45deg);
  }

  #hamburger.active span:nth-of-type(2) {
    opacity: 0;
  }

  #hamburger.active span:nth-of-type(3) {
    top: 20px;
    transform: rotate(-45deg);
  }

  .menu {
    position: fixed;
    z-index: 100;
    background: #fff;
    width: 100%;
    height: 100%;
    top: 0;
    left: -100%;
    transition: 0.5s;
  }

  .menu.open {
    left: 0;
  }

  .menu-logo {
    font-size: 1.5rem;
    font-weight: bold;
    margin: 10px 20px;
  }

  .menu-content a {
    font-size: 1.2rem;
    color: #000;
    display: block;
    margin: 20px;
    border-bottom: 1px solid #eee;
  }
}
</style>