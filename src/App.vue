<template>
  <div id="app">
    <div class="header">
      I am header!
    </div>
    <header></header>
    <div class="tab">
      I am tab
    </div>
    <div class="content">
      I am content
    </div>
    <!--<img src="./assets/logo.png">-->
    <!--<router-view/>-->
  </div>
</template>

<script>
  import header from './components/header/header.vue';

  export default {
    components: {
      header: header
    }
  };
</script>

<style>

</style>
