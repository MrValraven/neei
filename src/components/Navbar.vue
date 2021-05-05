<template>

  <header class="header">
    <nav id="nav">
      <div class="logo">
              <router-link class="logoName" to="/">
                  <p>NeeiUE</p>
              </router-link>
          </div>
      <ul>
        <li><router-link class="navLinks" to="/">Home</router-link></li>
        <li><router-link class="navLinks" :to="{ name: 'Home' }">Notícias</router-link></li>
        <li><router-link class="navLinks" :to="{ name: 'Home' }">Contactos</router-link></li>
      </ul>
	</nav>
  </header>
    
  
</template>

<script>

export default {
  name: 'Navbar',
};
</script>

<style lang="scss">
.header {
  position: absolute;
	z-index: 10;
	width: 100%;
	opacity: 1;
	color: #fff;
	padding: 35px 100px 0;
  #nav {
    display: flex;
    justify-content: space-around;
    .logo {
      a {
        opacity: 1;
      }
      img {
        width: 200px;
        position: absolute;
        top: 15px;
        left: 40px;
      }
    }
    ul {
      display: flex;
      justify-content: center;
      align-items: center;
      li {
        padding: 10px;
        font-size: 22px;
        a {
          font-weight: bold;
          color: #000000;
          &.router-link-exact-active {
            border-bottom: 1px solid black;
          }
        }  
      }
    }
  }
}
</style>