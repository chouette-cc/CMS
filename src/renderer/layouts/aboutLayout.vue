<template>
  <div>
    <header class="header" />
    <h1>About Layout</h1>
    <AppLayoutLinks />
    <slot />
  </div>
</template>

<script>
import AppLayoutLinks from '@/layouts/AppLayoutLinks.vue'
export default {
  name: "AppLayoutHome",
  components: {
    AppLayoutLinks
  }
}
</script>

<style scoped>
.header {
  height: 5rem;
  background-color: red;
}
</style>