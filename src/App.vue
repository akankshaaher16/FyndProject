home<template>
  <div id="app">
    <!-- <sppu/> -->
    <homePage/>
    <!-- <signUp/> -->

  </div>
</template>

<script>
// import signUp from './components/signUp.vue'
import homePage from './components/homePage.vue'


export default {
  name: 'App',
  components: {
    // signUp
    homePage

  }
}
</script>

<style>
#app{
  text-align: center;
}
</style>
