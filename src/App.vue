<template>
  <div id="app">
    <Title />
    <Jumbotron />
  </div>
</template>

<script>
import Title from '@/components/title.vue';
import Jumbotron from '@/components/jumbotron.vue';
export default {
  name: 'App',
  components: {
    Title,
    Jumbotron,
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
  display: flex;
  height: 100%;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
</style>
