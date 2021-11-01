<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Monte seu Burger:</h1>
      <p>Formulario</p>
    </div>
  </div>
</template>

<script>
import Banner from "../components/Banner.vue";

export default {
  name: "Home",

  components: {
    Banner,
  },
};
</script>
