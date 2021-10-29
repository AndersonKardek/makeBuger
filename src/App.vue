<template>
  <Navbar />
  <router-view/> <!--Os coteudo da pasta viwes serão impressas aqui-->
  <Footer />
</template>

<script>
  import Navbar from "./components/Navbar.vue"
  import Footer from "./components/Footer.vue"

  export default {
    components: {
      Navbar,
      Footer,
    }
  }
</script>

<style>

</style>
