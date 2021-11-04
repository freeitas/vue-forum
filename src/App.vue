<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <page-home/>
</template>

<script>
import PageHome from '@/components/PageHome'
export default {
  name: 'App',
  components: {
    PageHome
  }
}
</script>

<style>
@import "assets/style.css";
</style>
