<template>
     <div class="carousel">
      <img src="~/assets/img/home-1.jpg" alt="home-1" />
      <img src="~/assets/img/home-2.jpg" alt="home-2" />
      <img src="~/assets/img/room-1.jpg" alt="room-1" />
      <img src="~/assets/img/landscape.jpg" alt="landscape" />
      <img src="~/assets/img/landscape-2.jpg" alt="landscape-2" />
    </div>
</template>


<style scoped lang="scss">
.carousel {
  display: flex;
  overflow: hidden;
  height: 30vh;
  gap: 6px;
  margin-bottom: 4px;

  img {
    border-radius: 8px;
    box-shadow: 0 0 4px 0 rgba(0,0,0,.4);
  }
}
</style>
