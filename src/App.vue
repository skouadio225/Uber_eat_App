<!-- ------------------ Template ------------------ -->

<template>
  <div id="app">
    <Home/>
  </div>
</template>

<!-- ------------------ Script ------------------ -->

<script>

import Home from './page/Home.vue';

export default {
  name: 'App',
  components: {
    Home,
  }
}
</script>

<!-- ------------------ Style ------------------ -->

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto%3Awght%40300%3B400%3B700&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
  padding: 20px;
}
</style>
