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
<template>
  <div>
    <Header />
    <NuxtPage />
    <Footer />
  </div>
</template>

<style lang="scss">
body {
  font-family: Lato,sans-serif;
  margin: 0;

  h3 {
    font-weight: 300;
  }
}
</style>
