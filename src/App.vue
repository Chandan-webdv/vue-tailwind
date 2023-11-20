<template>
  <img src="./assets/logo.png" alt="vue logo">
  <HelloWorld msg="Welcome to my side "/>
   <Home/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Home,
  }
}
</script>

<style>

</style>
