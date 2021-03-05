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
          <!-- <a class="nav-link" href="../index.html">
            <img src="../stylesheet/img/logotype-lg-dark.svg" alt="" width="114.14px">
          </a> -->
        </li>
        <li class="nav-item">
          <!-- <a class="nav-link" href="cart.html">
              <img src="../stylesheet/img/baseline-shopping_cart-24px.svg" alt="">
          </a> -->
        </li>
      </ul>
      <nav class="navbar navbar-light">
        <!-- <a class="navbar-brand" href="../index.html">
          <img src="../stylesheet/img/logo-all-dark.svg" height="40" class="d-inline-block align-top" alt="">
        </a> -->
        <ul class="nav justify-content-end">
          <li class="nav-item">
            <!-- <a class="nav-link" href="../index.html">首頁</a> -->
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link" href="product.html">甜點</a> -->
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link" href="login.html">登入</a> -->
          </li>
          <li class="nav-item">
            <!-- <a class="nav-link" href="cart.html">
              <img src="../stylesheet/img/baseline-shopping_cart-24px.svg" alt="">
            </a> -->
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style lang="scss">
// @import '@/assets/scss/_layout.scss';
</style>