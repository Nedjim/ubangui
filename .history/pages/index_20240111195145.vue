<script setup lang="ts">
const introduction = 'Désormais vous avez à Saint-Louis un motel attrayant et reposant: La Résidence UBANGUI.';
const paragraph1 = 'Située à Ndiawsir Lébou, à l entrée de Saint-Louis en venant de Dakar, La Résidence Ubangui est un site de rêve.';
const paragraph2 = 'Les toitures de ses cases en voûte vous plongent dans une ambiance authentique africaine.';
const paragraph3 = 'Sa cour onbragée de badamiers, frangipaniers, cocotiers, ... est un véritable petit coin des Caraïbes.'; 
</script>

<template>
  <div>
   <Carousel />
   <p>{{ introduction }}</p>
   <p>{{ paragraph1 }}</p>
   <p>{{ paragraph2 }}</p>
   <p>{{ paragraph3 }}</p>
  </div>
</template>
