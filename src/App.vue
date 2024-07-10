<template>
<NavBar/>
<FooterComp/>
  
</template>
<script>
import NavBar from'./components/NavBar.vue'
import FooterComp from'./components/Footer.vue'
export default{
  name:'App',
  components:{
    NavBar,FooterComp
  }
}
</script>
<style>

</style>
