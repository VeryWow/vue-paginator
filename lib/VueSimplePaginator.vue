<template lang="pug">
  .vue-simple-paginator
    slot(v-bind="_self")
      slot(name="prev")
      slot(name="next")
      slot(name="page-button")
      slot(name="delimiter")
      slot(name="start" v-bind="_self")
      slot(name="end")
</template>

<script>
  export default {
    name: 'vue-simple-paginator',
    data () {
      return {
        drp: 5
      }
    }
  }
</script>
