<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/vue.svg" class="logo" />
    <HelloWorld msg="Welcome to Your Vue.js + EC3 App" />
  </div>
</template>

<style scoped>
.logo {
  height: 10em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

</style>
