<template>
  <div id="app">
    <div class="d-flex">
    <certificate msg="Welcome to Your Vue.js App"/>
    </div>    
  </div>
</template>

<script>
import certificate from './components/certificate.vue'

export default {
  name: 'App',
  components: {
    certificate
  },

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
