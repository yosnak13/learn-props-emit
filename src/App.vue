<template>
  <div>
    <h1>Hello from APP.vue</h1>
    <Child greet='Hello with props' />
  </div>
</template>

<script>
import Child from './components/Child.vue'
export default {
  components: {
    Child
  }
}
</script>
