<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!--<HelloWorld msg="mesage x"/>-->
  <div class="sidebar" id="sidebar">
    <CardMenu />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import CardMenu from "./components/CardMenu.vue";
export default {
  name: 'App',
  components: {
    //HelloWorld
    CardMenu
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
  margin-top: 60px;
}
</style>
