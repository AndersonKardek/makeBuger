<template>
  <footer class="main-container">
    <h1>Gerenciar Pedidos</h1>
    <DashBoard />
  </footer>
</template>

<script>
import DashBoard from "../components/DashBoard.vue"

export default {
  name: "Pedidos",

  components: {
    DashBoard,
  }
};
</script>

<style scoped>

</style>