<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <NavBar/>
  <FooterComp/>
 
</template>

<script>

import Navbar from './components/NavBar.vue'
import FooterComp from './components/Footer.vue'
export default {
  name: 'App',
  components: {
Navbar,FooterComp
  }
}
</script>

<style>

</style>
