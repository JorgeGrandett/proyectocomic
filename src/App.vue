<template>
  <div id="app">
   <comic/>
  </div>
</template>

<script>
import comic from '@/components/comic.vue'
export default {
  name: 'App',
  components: {
    comic
  }
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
