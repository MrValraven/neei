<template>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

body {}

ul,
li {
  list-style-type: none;
}

a {
  text-decoration: none;
  cursor: pointer;

  &.router-link-exact-active {
    color: #42b983;
  }
}
</style>
