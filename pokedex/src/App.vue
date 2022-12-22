<template>
  <div id="app">
    <pokemon/>
  </div>
</template>

<script>
import Pokemon from "./components/Pokemon.vue";

export default {
  name: "app",
  components: {
    Pokemon
  }
};
</script>

<style>
@import url("https://use.fontawesome.com/releases/v5.8.2/css/all.css");

body {
  margin: 0;
  padding: 0;
}
#app {
  background-color: #000000;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100%25' height='100%25' viewBox='0 0 1600 800'%3E%3Cg %3E%3Cpolygon fill='%231a0222' points='1600 160 0 460 0 350 1600 50'/%3E%3Cpolygon fill='%23340344' points='1600 260 0 560 0 450 1600 150'/%3E%3Cpolygon fill='%234d0566' points='1600 360 0 660 0 550 1600 250'/%3E%3Cpolygon fill='%23670688' points='1600 460 0 760 0 650 1600 350'/%3E%3Cpolygon fill='%238108AA' points='1600 800 0 800 0 750 1600 450'/%3E%3C/g%3E%3C/svg%3E");
  background-attachment: fixed;
  background-size: cover;
}
</style>
