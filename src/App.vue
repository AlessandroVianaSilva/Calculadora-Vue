<template>
  <div id="calculadora">
    <Calculadora/>
  </div>
</template>

<script>
import Calculadora from './components/Calculadora.vue';

export default {
  name: 'App',
  components: {
    Calculadora,
  },
};
</script>

<style lang="scss">
body {
  background-color: #222;
  margin: 0;
  padding: 0;
}
#calculadora{
  font-family: 'Poppins', sans-serif;
  font-size: 1rem;
}
</style>
