<template>
  <div>
    <Header/>
    <index/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Header from '../components/header.vue'
import index from '../pages/index.vue'

export default Vue.extend({
  components: { index, Header },

})
</script>

<style lang="" scoped>

</style>
