<template>
  <main>

    <div class="nav">
      <div class="container">
        <router-link to="/" class="logo">
          <img src="./assets/img/svg.svg" alt="" class="logo-svg">
          <h1 class="logo-title">Ibn Sino<span>Education</span></h1>
        </router-link>
        <img src="./assets/img/burger.svg" alt="" class="burger">
        <div class="nav modal">
          <ul class="nav-list">
            <li class="nav-list__item"><router-link to="/">Asosiy</router-link></li>
            <li class="nav-list__item"><a href="#">Biz haqimizda</a></li>
            <li class="nav-list__item"><a href="#">O'qituvchilar</a></li>
            <li class="nav-list__item"><a href="#">Yutuqlar</a></li>
            <li class="nav-list__item"><a href="tel:+998948553366">Biz bilan bog'laning</a></li>
            <li class="nav-list__item"><router-link to="/location">Manzil</router-link></li>
          </ul>
        </div>
      </div>
    </div>
    <router-view></router-view>
    <div class="footer">
      <div class="container">
        <router-link to="/" class="logo">
          <img src="./assets/img/svg.svg" alt="" class="logo-svg">
          <h1 class="logo-title">Ibn Sino<span>Education</span></h1>
        </router-link>
        <ul class="footer-list">
          <li class="footer-list__item"><a href="tel:+998948553366">Biz bilan bog'laning</a></li>
          <li class="footer-list__item"><router-link to="/location">Manzil</router-link></li>
          <li class="footer-list__item"><a href="">Biz haqimizda</a></li>
          <li class="footer-list__item"><a href="">O'qituvchilar</a></li>
          <li class="footer-list__item"><a href="">Yutuqlar</a></li>
        </ul>
        <div class="social-network">
          <div class="item">
            <img src="./assets/img/telegram.png" alt="" class="item-img">
            <a href="https://t.me/Ibn_Sino_Education" class="item-title">Telegram</a>
          </div>
          <div class="item">
            <img src="./assets/img/instagram.png" alt="" class="item-img">
            <a href="https://www.instagram.com/ibnsinoeducationofficial" class="item-title">Instagram</a>
          </div>
          <div class="item">
            <img src="./assets/img/facebook.svg" alt="" class="item-img">
            <router-link to="/" class="item-title">Facebook</router-link>
          </div>
          <div class="item">
            <img src="./assets/img/you tube.png" alt="" class="item-img">
            <a href="https://www.youtube.com/@ibnsinoeducation3090" class="item-title">You Tube</a>
          </div>
        </div>
      </div>
      <div class="uzb">O'zbekiston Respublikasi 2024©</div>
    </div>

  </main>
</template>

<script setup>
import '@/assets/scss/main.scss'
</script>

<style lang="scss" scoped></style>