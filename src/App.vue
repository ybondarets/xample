<template>
  <div id="app">
    <navigation></navigation>
    <router-view/>
  </div>
</template>
<script>
  import Navigation from '@/components/Navigation';
  import { Component, Vue } from 'vue-property-decorator';

  @Component({
    components: {
      Navigation,
    },
  })
  export default class App extends Vue {}
</script>
<style lang="scss">
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
</style>
