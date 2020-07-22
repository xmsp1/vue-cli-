<template>
  <div id="app">
    <Home></Home>
    <router-view/>
  </div>
</template>

<style>

</style>

<script>
import Home from '@/views/Home.vue'

export default {
  components: {
    Home
  }
}
</script>
