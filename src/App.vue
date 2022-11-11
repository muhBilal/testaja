<template>
  <div id="app">
    <Sidebar />
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue';
import './assets/css/tailwind.css';
import './assets/css/sidebar.css';

export default {
  name: 'App',
  components: {
    Sidebar,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>