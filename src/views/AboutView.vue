<template>
  <NavBar/>
  <div class="about">
    <h1>About</h1>
  </div>
  <Footer/>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
export default {
  components: {
    NavBar,
    Footer
  }
}
</script>
<style scoped>
</style>
