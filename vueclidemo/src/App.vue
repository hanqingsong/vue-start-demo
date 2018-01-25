<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <Rate></Rate>
    <Button></Button>
  </div>
</template>

<script>
import Rate from './components/Rate.vue'
import Button from './components/Button.vue'
export default {
  name: 'App',
  components: { Rate, Button }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>