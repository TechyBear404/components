<script setup lang="ts">
import Nav from "./Nav.vue";
import Footer from "./Footer.vue";
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header>
      <Nav />
    </header>
    <main class="flex-grow py-5">
      <div class="container mx-auto">
        <slot name="title" />
        <slot name="content" />
      </div>
    </main>
    <Footer />
  </div>
</template>
