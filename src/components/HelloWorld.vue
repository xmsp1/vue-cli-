<template>
  <div>
    <h1>123</h1>
    <slot name="slot"></slot>
    <slot>hello slot</slot>
    <div><slot>22</slot></div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style>
</style>
