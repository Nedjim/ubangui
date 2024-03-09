<template>
  <header>
    <nav>
      <img class="logo" src="~/assets/img/logo.jpg" alt="logo-ubangui" />
      <ul>
        <li><NuxtLink to="/home">Home</NuxtLink></li>
        <li><NuxtLink to="/rooms">Rooms</NuxtLink></li>
        <li><NuxtLink to="/reservations">Réservations</NuxtLink></li>
        <li><NuxtLink to="/contact">Contact</NuxtLink></li>
      </ul>
    </nav>
    <div class="separador"></div>
  </header>
</template>

<style scoped lang="scss">
.logo {
  width: 150px;
}

header {
  padding: 16px;
}

nav {
  display: flex;
  margin-bottom: 24px;
  ul {
    width: 40%;
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

.separador {
  overflow: hidden;
  height: 20px;
}

.separador:after {
  content: '';
  display: block;
  width: 90%;
  height: 30px;
	margin: -30px auto 0;
  border-radius: 120px / 10px;
  box-shadow: 0px 0px 8px rgba(0,0,0,.6);
}
</style>
