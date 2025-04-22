<script setup lang="ts">
const route = useRoute();
//params er et objekt som indeholder hvad end der er i []
const id = route.params.id;
</script>

<template>
<p>du er bruger nummer: {{id}}</p>
</template>

<style scoped>

</style>