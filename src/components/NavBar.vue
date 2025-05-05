<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav class="nav-text">
    <RouterLink to="/">Home</RouterLink> <span> | </span>
    <RouterLink to="/Projects">Projects</RouterLink> <span> | </span>
    <RouterLink to="/Skills">Skills</RouterLink>
  </nav>
  <br />
</template>

<style lang="css">
.nav-text {
  font-size: 1.25em;
}
</style>
