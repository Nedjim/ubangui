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
    <div>
      <img src="~/assets/img/home.jpg" alt="home" />
      <img src="~/assets/img/home.jpg" alt="home-2" />
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
    // color: #CD1E59;
    // background: $secondary;
  }
}
</style>
