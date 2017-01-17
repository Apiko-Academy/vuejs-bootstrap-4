<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <bootstrap-example></bootstrap-example>

  </div>
</template>

<script>
import $ from 'jquery';
import Hello from './components/Hello';
import BootstrapExample from './components/BootstrapExample';

export default {
  name: 'app',
  components: {
    Hello,
    BootstrapExample,
  },
  mounted() {
    $('.carousel').carousel();
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
