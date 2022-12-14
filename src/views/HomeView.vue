<template>
  <NavBar/>
  <div class="home">
    <h1 class="text-center">Home</h1>
    <img alt="Vue logo" src="https://i.postimg.cc/zXDrJc90/LOGO.png">
    <br>
    <img src="https://i.postimg.cc/XvpkZvFM/Volkano-Volkano-Logo-1.png" alt="volkano">
  </div>
  <Footer/>
</template>
<script>
import NavBar from '../components/NavBar.vue'
import Footer from '../components/Footer.vue'
export default {
  name: 'HomeView',
  components: {
    NavBar,
    Footer
  }
}
</script>
