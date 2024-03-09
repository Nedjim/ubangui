<script setup lang="ts">
const {title} = defineProps<{
  title: string
}>()
</script>

<template>
  <div class="title-wrapper">
    <font-awesome-icon class="icon" icon="fa-solid fa-sun" />
    <h2>{{ title }}</h2>
    <font-awesome-icon class="icon" icon="fa-solid fa-sun" />
  </div>
</template>

<style scoped lang="scss">

.title-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;

  h2 {
    margin: 0 12px;
  }
}
.icon {
  color: darkslategray;
}
</style>