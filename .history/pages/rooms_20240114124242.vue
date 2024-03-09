<script setup lang="ts">
const content =
  "Toutes les chambres ont la même dimension (24 m2). Les plafonds en voûte sont élevés, ce qui favorise une bonne aération et le maintien des chambres dans une fraîcheur agréable durant une bonne partie de la journée. Les chambres sont appelées des « Maisons ». Chaque chambre ou « Maison » a une couleur spécifique. Ainsi nous avons « La  Maison blanche », « La Maison bleue », « La Maison rouge » et « La Maison jaune ». Elles sont équipées de climatiseurs, chauffe-eau, frigos-bar,  et ont des dispositifs  pour téléviseurs, wifi, etc. Les prix des chambres varient en fonction du nombre  d’occupants :";
</script>

<template>
  <div class="rooms-wrapper">
    <PageTitle title="Description" />
    <div>
      <p>{{ content }}</p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.rooms-wrapper {
  padding: 30px 80px;
}
</style>
