<script setup lang="ts">
const route = useRoute()
const slug = route.params.slug;
</script>

<template>
<div>
  <p>DU LÆSER LIGE NU {{ slug }}</p>
</div>
</template>

<style scoped>

</style>