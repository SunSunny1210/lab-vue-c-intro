<script setup>
import Header from './components/Header.vue'

</script>

<template>
  <div id="app">
    <Header></Header>
    <MainSection></MainSection>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&display=swap');

  body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    max-width: 600px;
    font-family: 'Inter', sans-serif;
  }
</style>