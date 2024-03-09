<script setup lang="ts">
const region_intro =
  "La région de Saint-Louis est située au Nord-Est du Sénégal. Elle couvre une superficie de 44 173 km2. Elle est limitée au Nord par la République islamique de Mauritanie, au Sud par la région de Louga, à l Ouest par l Océan Atlantique et à l’Est par la région de Matam. Saint-Louis appartient à la zone sahélienne.";
const region_paragraph1 =
  "Son histoire est surtout marquée par le gouverneur Faidherbe qui y a laissé une place et un pont qui portent son nom. La région compte deux saisons : la saison sèche qui va de novembre à mai et la saison des pluies qui, elle, va de juin à octobre. Sur le plan culturel et éducatif, Saint-Louis est célèbre à travers son Festival International de Jazz qui a lieu chaque année et son l Université Gaston Berger réputée pour son excellence.";

const residence_intro =
  "Désormais vous avez à Saint-Louis un motel attrayant et reposant: La Résidence UBANGUI.";
const residence_paragraph1 =
  "Située à Ndiawsir Lébou, à l entrée de Saint-Louis en venant de Dakar, La Résidence Ubangui est un site de rêve. Les toitures de ses cases en voûte vous plongent dans une ambiance authentique africaine. Sa cour onbragée de badamiers, frangipaniers, cocotiers, ... est un véritable petit coin des Caraïbes.";
const residence_paragraph2 =
  "Elle vous assure calme, tranquilité et sérénité. Et si vous êtes artiste, écrivain ou chercheur, vous avez un cadre idéal, propice à la création.";
const residence_paragraph3 =
  "Pour vos séjours à Saint-Louis, choisissez La Résidence Ubangui. Vous ne regretterez jamais !";
</script>

<template>
  <div>
    <div class="presentation">
      <div>
        <h2><font-awesome-icon icon="fa-solid fa-city" /> Présentation de la région</h2>
        <p>{{ region_intro }}</p>
        <p>{{ region_paragraph1 }}</p>
      </div>
      <div>
        <h2>Présentation de la résidence</h2>
        <p>{{ residence_intro }}</p>
        <p>{{ residence_paragraph1 }}</p>
        <p>{{ residence_paragraph2 }}</p>
        <p>{{ residence_paragraph3 }}</p>
      </div>
    </div>
    <div class="carouselWrapper">
      <Carousel />
    </div>
  </div>
</template>
<style scoped lang="scss">
.presentation {
  padding: 30px 80px;
  margin-bottom: 24px;
}

.carouselWrapper {
  margin-bottom: 4px;;
}
</style>
