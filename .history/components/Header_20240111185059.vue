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
  </header>
</template>

<style scoped lang="scss">
nav {
  width: 50%;

  ul {
  display: flex;
  justify-content: space-between;
  // color: #CD1E59;
  // background: $secondary;
}
}
</style>
