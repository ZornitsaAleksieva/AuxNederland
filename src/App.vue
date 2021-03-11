<template>

<div class=".background"></div>

  <router-view/>
</template>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2B2B2B;
}

#nav {
  padding: 70px;
}

#nav a {
  font-weight: bold;
  color: #DB3733;
}

#nav a.router-link-exact-active {
  color: #DB3733;
}
</style>
