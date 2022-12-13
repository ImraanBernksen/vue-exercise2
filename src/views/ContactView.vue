<template>
    <NavBar/>
    <div>
        <Contact/>
    </div>
</template>
<script>
import Contact from "../components/ContactForm.vue";
import NavBar from "../components/NavBar.vue";
export default {
    components: {
        Contact,
        NavBar
    }
}
</script>
<style scoped>
</style>