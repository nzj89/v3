<template>
  <div id="app">
    <MenuBar></MenuBar>
    <HomePage msg="Welcome to Your Vue.js App"/>
  </div>
  
</template>

<script>
import HomePage from './components/HomePage.vue'
import MenuBar from './components/MenuBar.vue'

export default {
  name: 'App',
  components: {
    HomePage,
    MenuBar
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
}

body{
  background-color: rgb(5, 5, 5);
  padding: 0;
  margin: 0;
}
</style>
