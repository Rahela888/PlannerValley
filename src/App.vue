<template>
  <nav>
    <router-link to="/home">Home</router-link> |
    <router-link to="/login">Login</router-link> |
    <router-link to="/register">Register</router-link> |
    <router-link to="/manag">Manage</router-link> |
    <router-link to="/chest">Chest</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family:Press Start 2P, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
