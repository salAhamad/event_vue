<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="First App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">

// @import '@/assets/scss/style.scss';
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  background-color: $green;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  color: $white;
  @include flexCenter();
}
</style>
