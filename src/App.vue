<template>
  <img alt="Vue logo" src="./assets/beyond-logo.png" style="width: 50%;">
  <HelloWorld msg="Welcome to my Beyond App" style=" font-size: 20px"/>
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
  font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color:#F19F05;
  margin-top: 60px;
  
 
}
body{
  background-color:#e1dddd;
}
</style>
