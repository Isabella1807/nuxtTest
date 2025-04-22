<script setup lang="ts">

</script>

<template>
  <nav>
    <ul class="navList">
      <li>
        <NuxtLink to="/" class="noStyle">Forside</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about" class="noStyle">About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/contact" class="noStyle">Kontakt</NuxtLink>
      </li>
    </ul>
  </nav>
</template>

<style scoped lang="scss">
.navList {
  background-color: lightgrey;
  display: flex;
  gap: 1rem;

  li {
    list-style: none;
    &:hover {
      background-color: white;
      padding: 0 1rem;
    }

    .noStyle{
      text-decoration: none;
      color: black;
    }
  }
}
</style>