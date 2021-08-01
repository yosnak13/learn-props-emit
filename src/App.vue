<template>
  <div>
    <h1>Hello from APP.vue</h1>
    <p>parent_num: {{ parent_num }}</p>
    <Child @my-click='parent_num = $event' />
  </div>
</template>

<script>
import Child from './components/Child.vue'
export default {
  data: function(){
    return {
      parent_num: 100
    }
  },
  components: {
    Child
  }
}
</script>
