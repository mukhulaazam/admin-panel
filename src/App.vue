<script setup lang="ts">
import TopHeader from './components/TopHeader.vue';
import TopNav from './components/NavBar.vue';
import Status from './components/StatusBar.vue';
import Graph from './components/GraphTotal.vue';

</script>
<template>
  <header>
    <TopHeader></TopHeader>
  </header>
  <nav>
    <TopNav></TopNav>
  </nav>
  <main>
    <Status/>
    <Graph/>
  </main>
  <footer>
    
  </footer>

</template>
<style>
@import './assets/css/bootstrap.min.css';
@import './assets/css/font-awesome.min.css';
@import './assets/css/owl.carousel.css';
@import './assets/css/owl.theme.css';
@import './assets/css/owl.transitions.css';
@import './assets/css/meanmenu/meanmenu.min.css';
@import './assets/css/animate.css';
@import './assets/css/normalize.css';
@import './assets/css/scrollbar/jquery.mCustomScrollbar.min.css';
@import './assets/css/jvectormap/jquery-jvectormap-2.0.3.css';
@import './assets/css/notika-custom-icon.css';
@import './assets/css/wave/waves.min.css';
@import './assets/css/main.css';
@import './assets/css/style.css';
@import './assets/css/responsive.css';
</style>
