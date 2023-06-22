<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <img src="./assets/dog.jpg" alt="dog dog">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <div>제가 만든 VUE 프로젝트 업로드</div>
  <div>!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!</div>
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
