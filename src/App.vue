<template>
  <div id="app">
    <div class="container-text">TIC TAC TOE</div>
    <div class="container-game">
      <table-component></table-component>
    </div>
  </div>
</template>

<script>
import TableComponent from "./components/TableComponent.vue";
export default {
  name: "App",
  components: {
    TableComponent,
  },
  mounted() {
    // this.$store.commit("increment");
    // console.log(this.$store.state.count);
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro&family=Roboto:wght@300&display=swap");
#app {
  font-family: "Be Vietnam Pro", sans-serif;
}
.container-text {
  font-size: 35px;
  font-weight: bold;
  text-align: center;
  margin-top: 40px;
}
.container-game {
  text-align: center;
}
</style>
