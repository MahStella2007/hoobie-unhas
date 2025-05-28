<template>
  <div>
    <Header />
    <Sobre />
    <Footer />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Sobre from './components/Sobre.vue'
import Footer from './components/Footer.vue'
</script>

<style>
body {
  margin: 0;
  font-family: 'Comic Sans MS', cursive, sans-serif;
  background-color: #FFFFFF;
  color: #C05050;
}
main {
  padding: 20px;
}
</style>
