<template>
    <Navbar />
    <router-view />
</template>

<script>
export default {
    components: { Navbar },
};
import Navbar from "./components/Navbar.vue";
</script>
<style>
body {
    backdrop-filter: #f2f2f2;
}
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    max-width: 600px;
    margin: 0 auto;
    color: #555;
}
body {
    background-color: #f2f2f2f2;
}
</style>
