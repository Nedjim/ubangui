<template>
  <header class="test">
    <nav>
      <ul>
        <li><NuxtLink to="/home">Home</NuxtLink></li>
        <li><NuxtLink to="/rooms">Rooms</NuxtLink></li>
        <li><NuxtLink to="/reservations">Réservations</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
      </ul>
    </nav>
    <div class="carousel">
      <img src="~/assets/img/home.jpg" alt="home" />
      <img src="~/assets/img/home-2.jpg" alt="home-2" />
    </div>
  </header>
</template>

<style scoped lang="scss">
nav {
  width: 50%;

  ul {
    display: flex;
    justify-content: space-between;
    li {
      list-style-type: none;
      a {
        text-decoration: none;
        color: black;
      }
    }
  }
}

.carousel {
  display: flex;
  overflow: hidden;
  height: 50vh;
  gap: 4px;
}
</style>
