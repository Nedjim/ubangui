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
  </header>
</template>

<style scoped lang="scss">
.logo {
  width: 200px;
}

nav {
  display: flex;
  margin-bottom: 40px;
  ul {
    width: 50%;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    li {
      list-style-type: none;
      a {
        text-decoration: none;
        color: black;
      }
    }
  }
}
</style>
