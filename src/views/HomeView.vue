<template>
  <NavBar/>
  <div class="home">
    <h1 class="text-center">Home</h1>
    <img alt="Vue logo" src="https://i.postimg.cc/zXDrJc90/LOGO.png">
  </div>
</template>
<script>
import NavBar from '../components/NavBar.vue'
export default {
  name: 'HomeView',
  components: {
    NavBar
  }
}
</script>
