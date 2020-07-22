<template>
  <div class="home">
    <hello-world >
      <h1 slot="slot">comes to slot</h1>
     <!-- <h2>hello h2</h2>
      <h1>hello h1</h1> -->
    </hello-world>
   <!-- <HelloWorld msg="Welcome to Your Vue.js App">
      <h2 name="slot">666</h2>
      <h1>come</h1>
    </HelloWorld> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
