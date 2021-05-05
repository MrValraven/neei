<template>
  <router-view/>
</template>

<style lang="scss">
@import url("https://use.fontawesome.com/releases/v5.15.2/css/all.css");
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300&display=swap');
@import url('./colors.scss');


#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

body {
  overflow-x: hidden;
}

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
