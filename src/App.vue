<template>
  <main>
    <div class="container">
      <div class="nav">
        <router-link to="/" class="logo">
          <img src="./assets/img/svg.svg" alt="" class="logo-svg">
          <h1 class="logo-title">Ibn Sino<span>Education</span></h1>
        </router-link>
        <ul class="nav-list">
          <li class="nav-list__item"><a href="tel:+998948553366">Biz bilan bog'laning</a></li>
          <li class="nav-list__item"><a href="#">Manzil</a></li>
          <li class="nav-list__item"><a href="#">Biz haqimizda</a></li>
          <li class="nav-list__item"><a href="#">O'qituvchilar</a></li>
          <li class="nav-list__item"><a href="#">Yutuqlar</a></li>
        </ul>
      </div>
      <video controls class="banner"><source src="./assets/video/8qqam39vpufbm7jypern.mp4"></video>
    </div>
  </main>
</template>

<script setup>
import '@/assets/scss/main.scss'
</script>

<style lang="scss" scoped></style>