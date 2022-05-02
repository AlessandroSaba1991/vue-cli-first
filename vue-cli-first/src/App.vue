<template>
  <div id="app">
    <Title_/>
    <Jumbo_/>
    <h3>Oleeee</h3>
  </div>
</template>

<script>
import Title_ from "./components/Title.vue";
import Jumbo_ from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title_,
    Jumbo_,
  },
};
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
