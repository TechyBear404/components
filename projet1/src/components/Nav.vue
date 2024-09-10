<script setup lang="ts">
import NavLink from "./NavLink.vue";
import { ref } from "vue";

const isMenuOpen = ref(false);
</script>

<template>
  <nav class="bg-gray-500 p-2">
    <div :class="{ 'hidden md:flex': !isMenuOpen }">
      <ul>
        <NavLink url="#" text="Home" />
      </ul>
    </div>
  </nav>
</template>
