<template>
  <div class='.main-container'>
    <Layout />
  </div>
</template>

<script>
import Layout from './layout/Layout.vue';

export default {
  name: 'App',
  components: {
    Layout
  }
}
</script>

<style>
#app {
  margin: 12px;
  font-size: 100%;
  font-family: 'Open Sans', sans-serif;
  color: white;
  height: 100%;
  background: linear-gradient(to bottom, rgb(43, 50, 178) 0%, rgb(20, 136, 204) 100%);
  background-repeat: no-repeat;
  background-attachment: fixed;
}
</style>
