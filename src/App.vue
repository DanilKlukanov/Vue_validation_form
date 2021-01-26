<template>
  <div id="app">
    <ValidationForm></ValidationForm>
  </div>
</template>

<script>
import ValidationForm from '@/components/ValidationForm.vue'

export default {
  name: 'App',
  components: {
    ValidationForm
  },
      loaders: {
        scss: 'vue-style-loader!css-loader!sass-loader', // <style lang="scss">
        sass: 'vue-style-loader!css-loader!sass-loader?indentedSyntax' // <style lang="sass"
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
