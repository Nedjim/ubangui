<script setup lang="ts">
const introduction =
  "Désormais vous avez à Saint-Louis un motel attrayant et reposant: La Résidence UBANGUI.";
const paragraph1 =
  "Située à Ndiawsir Lébou, à l entrée de Saint-Louis en venant de Dakar, La Résidence Ubangui est un site de rêve. Les toitures de ses cases en voûte vous plongent dans une ambiance authentique africaine. Sa cour onbragée de badamiers, frangipaniers, cocotiers, ... est un véritable petit coin des Caraïbes.";

</script>

<template>
  <div>
    <Carousel />
    <div>
      <p>{{ introduction }}</p>
      <p>{{ paragraph1 }}</p>
    </div>
  </div>
</template>
