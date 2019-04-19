<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <t1 msg="t1 parent"/>
    <my_component1></my_component1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import t1 from "./components/t1.vue"
import my_component1 from './components/my_component1.vue';

export default {
  name: 'app',
  components: {
    HelloWorld,
    t1,
    my_component1
  }
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
