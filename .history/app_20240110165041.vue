<script setup lang="ts">
useHead({
  title: "Ubangui",
  meta: [{ name: "Residence Ubangui", content: "Sénégal" }],
  bodyAttrs: {
    class: "test",
  },
  script: [{ innerHTML: "console.log('Hello world')" }],
});
</script>

<style lang="scss">
@use "~/assets/scss/main.scss";
</style>

<template>
  <div>
    <Header />
    <NuxtPage />
    <Footer />
  </div>
</template>
