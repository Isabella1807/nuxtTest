<script setup lang="ts">
//for at kunne destructere data på flere paths, kan man navngive ved med :navn
const {data: hello} = await useFetch('/api/hello')
</script>

<template>
  <div>
    <h1>Forside?</h1>
    <p>{{ hello?.hello}}</p>
  </div>
</template>

<style scoped>

</style>