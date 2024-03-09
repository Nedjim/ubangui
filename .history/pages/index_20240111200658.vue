<script setup lang="ts">
const introduction =
  "Désormais vous avez à Saint-Louis un motel attrayant et reposant: La Résidence UBANGUI.";
const paragraph1 =
  "Située à Ndiawsir Lébou, à l entrée de Saint-Louis en venant de Dakar, La Résidence Ubangui est un site de rêve. Les toitures de ses cases en voûte vous plongent dans une ambiance authentique africaine. Sa cour onbragée de badamiers, frangipaniers, cocotiers, ... est un véritable petit coin des Caraïbes.";
const paragraph2 = "Elle vous assure calme, tranquilité et sérénité. Et si vous êtes artiste, écrivain ou chercheur, vous avez un cadre idéal, propice à la création.";
const paragraph3 = "Pour vos séjours à Saint-Louis, choisissez La Résidence Ubangui. Vous ne regretterez jamais !";
</script>

<template>
  <div>
    <Carousel />
    <div class="presentation">
      <p>{{ introduction }}</p>
      <p>{{ paragraph1 }}</p>
      <p>{{ paragraph2 }}</p>
      <p>{{ paragraph3 }}</p>
    </div>
  </div>
</template>
<style scoped lang="scss">
.presentation {
  width: 70%;
  text-align: center;
}
</style>

