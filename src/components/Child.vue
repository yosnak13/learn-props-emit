<template>
  <div>
    <p>{{ greet }}</p>
  </div>
</template>

<script>
export default {
  props: {
    greet: {
      type: String,
      default: 'hogehoge'
    },
  },
}
</script>
