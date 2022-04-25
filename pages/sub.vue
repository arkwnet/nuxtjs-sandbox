<template>
  <div>
    <p>Sub Page</p>
    <p><NuxtLink to="/">Return to top page.</NuxtLink></p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'SubPage',
})
</script>
