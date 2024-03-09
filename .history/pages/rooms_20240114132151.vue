<script setup lang="ts">
const conversion_cfa_euros = 0.0015;
const room_single_cfa = 20000;
const room_double_cfa = 25000;
const room_single_euros = `${room_single_cfa * conversion_cfa_euros} euros`;
const room_double_euros = `${room_double_cfa * conversion_cfa_euros} euros`;

const rooms_paragraph_1 = "Toutes les chambres ont la même dimension (24 m2).";
const rooms_paragraph_2 =
  "Les plafonds en voûte sont élevés, ce qui favorise une bonne aération et le maintien des chambres dans une fraîcheur agréable durant une bonne partie de la journée.";
const rooms_paragraph_3 =
  "Les chambres sont appelées des « Maisons ». Chaque chambre ou « Maison » a une couleur spécifique. Ainsi nous avons « La  Maison blanche », « La Maison bleue », « La Maison rouge » et « La Maison jaune ».";
const rooms_paragraph_4 =
  "Elles sont équipées de climatiseurs, chauffe-eau, frigos-bar,  et ont des dispositifs  pour téléviseurs, wifi, etc.";
const rooms_paragraph_5 =
  "Les prix des chambres varient en fonction du nombre  d’occupants :";

const room_single_title = "Single";
const room_single_details = `(${room_single_euros} + petit déjeuner) / nuit`;
const room_double_title = "Double";
const room_double_details = `(${room_double_euros} + petit déjeuner) / nuit`;
</script>

<template>
  <div class="rooms-wrapper">
    <PageTitle title="Chambres" />
    <div class="content">
      <p>{{ rooms_paragraph_1 }}</p>
      <p>{{ rooms_paragraph_2 }}</p>
      <p>{{ rooms_paragraph_3 }}</p>
      <p>{{ rooms_paragraph_4 }}</p>
      <p>{{ rooms_paragraph_5 }}</p>

      <ul>
        <li><span class="room_title">{{ room_single_title }}</span>: {{ room_single_details }}</li>
        <li><span class="room_title">{{ room_double_title }}</span>: {{ room_double_details }}</li>
      </ul>
    </div>
  </div>
</template>

<style scoped lang="scss">
.rooms-wrapper {
  padding: 30px 80px;

  .content {
    margin: 40px 0;

    .room_title {
      font-weight: bold;
    }
  }
}
</style>
