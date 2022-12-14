<template>
    <NavBar/>
    <div>
        <Contact/>
    </div>
    <Footer/>
</template>
<script>
import Contact from "../components/ContactForm.vue";
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
export default {
    components: {
        Contact,
        NavBar,
        Footer
    }
}
</script>
<style scoped>
</style>