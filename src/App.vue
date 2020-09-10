<template>
  <div id="app">
    <HelloWorld />
    <RecommendedJob/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import RecommendedJob from './components/RecommendedJob.vue'

export default Vue.extend({
  name: 'App',
  components: {
    HelloWorld,
    RecommendedJob
  }
})
</script>

<style>
</style>
