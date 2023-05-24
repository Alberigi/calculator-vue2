<template>
  <div id="app">
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./pages/Calculator.vue";

export default {
  name: "App",
  components: {
    Calculator,
  },
};
</script>

<style>
body {
  margin: 0px;
}

#app {
  display: flex;
  display-direction: columns;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>
