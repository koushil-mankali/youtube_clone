<script setup lang="ts">
import Navbar from "./NavbarComponents/Navbar.vue";
</script>

<template>
  <div class="root">
    <aside class="sidebar">Sidebar</aside>
    <div class="mainbdy">
      <Navbar />
      <slot></slot>
    </div>
  </div>
</template>

<style scoped>
.root{
    display: flex;
}

.sidebar{
    width: 70px;
    padding: 10px;
    background-color: crimson;
}

.mainbdy{
    width: 100%;
}
</style>
