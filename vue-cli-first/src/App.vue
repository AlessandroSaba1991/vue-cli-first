<template>
  <div id="app">
    <Title_/>
  </div>
</template>

<script>
import Title_ from './components/Title.vue'


export default {
  name: 'App',
  components: {
    Title_
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
