<template>
  <div id="app2">
    <h1>Calculadora</h1>
    <Calculator />
    </div>
</template>

<script>
import Calculator from "./main/Calculator.vue"
//Regra multi-word TodoDisplay TodoCalculator https://eslint.vuejs.org/rules/multi-word-component-names.html
export default {
  components: { Calculator }
}
</script>

<style>
@font-face{
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}
* {
   font-family: "RobotoMono", monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;

  color: #fff;
 background:  linear-gradient(to right, rgb(252, 0, 255), rgb(0, 219, 222));
}
</style>
