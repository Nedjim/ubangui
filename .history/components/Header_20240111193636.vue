<template>
  <header class="test">
    <nav>
      <img class="logo" src="~/assets/img/logo.jpg" alt="logo-ubangui" />
      <ul>
        <li><NuxtLink to="/home">Home</NuxtLink></li>
        <li><NuxtLink to="/rooms">Rooms</NuxtLink></li>
        <li><NuxtLink to="/reservations">Réservations</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
      </ul>
    </nav>
    <div class="carousel">
      <img src="~/assets/img/home-1.jpg" alt="home-1" />
      <img src="~/assets/img/home-2.jpg" alt="home-2" />
      <img src="~/assets/img/room-1.jpg" alt="room-1" />
      <img src="~/assets/img/landscape.jpg" alt="landscape" />
    </div>
  </header>
</template>

<style scoped lang="scss">
nav {
  display: flex;
  justify-content: space-between;
  ul {
    width: 50%;
    li {
      list-style-type: none;
      a {
        text-decoration: none;
        color: black;
      }
    }
  }
}

.logo {
  width: 200px;
}

.carousel {
  display: flex;
  overflow: hidden;
  height: 50vh;
  gap: 4px;
}
</style>
