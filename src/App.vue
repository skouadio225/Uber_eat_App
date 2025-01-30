<!-- ------------------ Template ------------------ -->

<template>
  <div id="app">
    <RestaurantCard/>
    <RestaurantCard/>
    <RestaurantCard/>
  </div>
</template>

<!-- ------------------ Script ------------------ -->

<script>

import RestaurantCard from './components/RestaurantCard.vue';

export default {
  name: 'App',
  components: {
    RestaurantCard
  }
}
</script>

<!-- ------------------ Style ------------------ -->

<style>
@import url('./style/reset.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto%3Awght%40300%3B400%3B700&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
}
</style>
