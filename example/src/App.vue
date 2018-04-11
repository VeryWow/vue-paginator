<template>
  <div id="app">
    <vue-simple-paginator>
      <div slot-scope="{ _data }" id="asd">
        <div slot="start"><pre>{{ _data }}</pre></div>
      </div>
    </vue-simple-paginator>
  </div>
</template>

<script>
  import VueSimplePaginator from '../../lib'

  export default {
    components: {
      VueSimplePaginator
    },
    name: 'app'
  }
</script>
