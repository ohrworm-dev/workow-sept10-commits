<template>
  <div id="app">
    <Left />
    <Infobar/>
    <RecommendedJob/>
  </div>
</template>

<script>
import Left from './components/Left.vue'
import Infobar from './components/Infobar.vue'
import RecommendedJob from './components/RecommendedJob.vue'

export default {
  name: 'App',
  components: {
    Left,
    Infobar,
    RecommendedJob
  }
}
</script>

<style>
</style>
