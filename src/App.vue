<template>
  <div id="app">
    <form-sample></form-sample>
  </div>
</template>

<script>
import FormSample from "@/components/FormSample";

export default {
  name: 'App',
  components: {
    FormSample
  }
}
</script>

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
