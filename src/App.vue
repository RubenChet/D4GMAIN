<template>
  <div id="app">
    <Navbar/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
  }
}
</script>

<style>
body{
  margin: 0!important;
}
.vs-navbar-content{
  position: relative!important;
}
</style>
