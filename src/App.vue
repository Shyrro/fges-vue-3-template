<script>
import { defineComponent } from 'vue'
import Calculcatrice from './components/Calculcatrice.vue';

export default defineComponent({
  name: 'App',
  components: {
    Calculcatrice
  }
});
</script>

<template>
  <Calculcatrice />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
