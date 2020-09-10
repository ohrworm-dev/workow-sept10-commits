<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <RecommendedJob/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import RecommendedJob from './components/RecommendedJob.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    RecommendedJob
  }
}
</script>

<style>
</style>
