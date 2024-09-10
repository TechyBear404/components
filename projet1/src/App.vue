<script setup lang="ts">
import Layout from "./components/Layout.vue";
import Button from "./components/Button.vue";
</script>

<template>
  <Layout>
    <template v-slot:title>
      <h1 class="text-3xl">Home</h1>
    </template>

    <template v-slot:content>
      <p>Welcome to the home page</p>
      <div>
        <Button>Click me!</Button>
      </div>
    </template>
  </Layout>
</template>
