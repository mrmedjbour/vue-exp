<template>
  <div>
    <h1>You are on Event page.</h1>
    <span id="id">Page Number {{ id }} </span>
  </div>
</template>

<script>
export default {
  name: "EventView",
  props:[
      'id',
  ],
  computed: {

  }
}
</script>

<style scoped>

</style>