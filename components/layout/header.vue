<template>
  <header class="sticky-top bg-nothing">
    <div class="container">
      <!-- Image and text -->
      <ul class="nav mobile">
        <!--Hamburger menu toggle button-->
        <li class=".nav-item">
          <a href="#" class="nav-link menu-trigger" id="menu-btn">
            <span></span>
            <span></span>
            <span></span>
          </a>
        </li>
        <div class="menu-container">
          <ul>
            <li>
              <nuxt-link to="/" class="nav-link">首頁</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/" class="nav-link">甜點</nuxt-link>
            </li>
            <li>
              <nuxt-link to="/" class="nav-link">登入</nuxt-link>
            </li>
          </ul>
        </div>
        <li class="nav-item">
          <nuxt-link to="/">
            <img src="../../assets/images/logotype-lg-dark.svg" alt="" width="114.14px">
          </nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to="/cart" class="nav-link">
            <img src="../../assets/images/baseline-shopping_cart-24px.svg" alt="">
          </nuxt-link>
        </li>
      </ul>
      <nav class="navbar navbar-light">
        <nuxt-link to="/" class="navbar-brand">
          <img src="../../assets/images/logo-all-dark.svg" height="40" class="d-inline-block align-top" alt="">
        </nuxt-link>
        <ul class="nav justify-content-end">
          <li class="nav-item">
            <nuxt-link to="/" class="nav-link">首頁</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/product" class="nav-link">甜點</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/login" class="nav-link">登入</nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/cart" class="nav-link">
              <img src="../../assets/images/baseline-shopping_cart-24px.svg" alt="">
            </nuxt-link>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss">
@import '@/assets/scss/_layout.scss';
</style>