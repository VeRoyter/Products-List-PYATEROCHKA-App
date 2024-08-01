<template>
  <div id="app">
    <h1>Список товаров магазина "ПЯТЕРОЧКА"</h1>
    <Products />
  </div>
</template>

<script>
import Products from './views/Products.vue';

export default {
  name: 'App',
  components: {
    Products,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #39bd6c;
  margin-top: 100px;
}

h1 {
  color: #bb3939;
}
</style>
