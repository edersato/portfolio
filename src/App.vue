<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style lang="scss">
html {
  background: #242122;
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

#app {
  background: #242122;
  text-align: center;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    text-decoration: none;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #b22222;
    }
  }
}
</style>
