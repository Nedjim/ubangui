<template>
  <header class="test">
    <nav>
      <ul>
        <li><NuxtLink to="/accueuil">Accueil</NuxtLink></li>
        <li><NuxtLink to="/chambres">Chambres</NuxtLink></li>
        <li><NuxtLink to="/reservations">Réservations</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">
.test {
  color: red;
  background: $secondary;
}
</style>
