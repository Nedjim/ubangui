<template>
  <header>
    <nav>
      <img class="logo" src="~/assets/img/logo.jpg" alt="logo-ubangui" />
      <ul>
        <li><NuxtLink to="/home">Home</NuxtLink></li>
        <li><NuxtLink to="/rooms">Rooms</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
      </ul>
    </nav>
  </header>
</template>

<style scoped lang="scss">
.logo {
  width: 150px;
}

header {
  padding: 16px 24px;
}

nav {
  display: flex;
  ul {
    width: 30%;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-left: 40px;
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
