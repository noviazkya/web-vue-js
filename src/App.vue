<template>
  <div>
    <navbar-component></navbar-component>
    <content1></content1>
    <Content2Vue></Content2Vue>
    <Content3></Content3>
    <Content4></Content4>
    <Footer></Footer>
  </div>
</template>

<script setup>
import NavbarComponent from './components/Navbar.vue';
import Content1 from './components/Content1.vue';
import Content2Vue from './components/Content2.vue';
import Content3 from './components/Content3.vue';
import Content4 from './components/Content4.vue';
import Footer from './components/Footer.vue';
</script>