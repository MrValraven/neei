<template>

  <header class="header">
    <nav id="nav">
      <div class="logo">
              <router-link class="logoName" to="/">
                   <svg id="logo" width="75px" height="75px" data-name="Layer 2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 389.75 225.46" ><polygon class="cls-1" points="0 43.79 0 225.46 25.33 225.46 25.33 114.12 65.33 225.46 90 225.46 90 43.79 65 43.79 65 152.79 26.33 43.79 0 43.79"/><polygon class="cls-1" points="115.67 43.79 115.67 225.46 189 225.46 189 200.79 142 200.79 142 143.46 175.67 143.46 175.67 118.46 141.67 118.46 141.67 68.79 189 68.79 189 43.79 115.67 43.79"/><path class="cls-1" d="M1097.67,460h26.67v24.67h-26.67Z" transform="translate(-792 -416.21)"/><path class="cls-1" d="M1124.33,641.67v-146h-26.67v146Z" transform="translate(-792 -416.21)"/><path class="cls-1" d="M1075.43,460h.23v25h-5.86a43.33,43.33,0,0,1-.1-25Z" transform="translate(-792 -416.21)"/><path class="cls-1" d="M1062,485a51,51,0,0,1-.08-25H1049a63.74,63.74,0,0,0,.07,25H1062" transform="translate(-792 -416.21)"/><path class="cls-1" d="M1058.3,641.67h17.37V617h-47V559.67h33.67v-25h-34V485h13a71.52,71.52,0,0,1-.06-25h-39V641.67Z" transform="translate(-792 -416.21)"/><path class="cls-1" d="M1151.38,529.86,1147.3,524a63.18,63.18,0,0,0,2.17-101.81l4.62-6a70.76,70.76,0,0,1-2.43,114Z" transform="translate(-792 -416.21)"/><path class="cls-1" d="M1139.8,513.35l-4-5.75a43.09,43.09,0,0,0,1.48-69.44l4.57-5.95a50.59,50.59,0,0,1-1.74,81.53Z" transform="translate(-792 -416.21)"/></svg>
              </router-link>
          </div>
      <ul>
        <li><router-link class="navLinks activeNavLink" to="/">Home</router-link></li>
        <li><router-link class="navLinks" to="/" @click="scrollToElement(noticias)" >Notícias</router-link></li>
        <li><router-link class="navLinks" to="/" @click="scrollToElement(contactos)" >Contactos</router-link></li>
        <li><a href="https://drive.google.com/drive/u/2/folders/1D_gu7gswNzIVHXu0OnEK1x3OwLy7sIaF" target="_blank" rel="nooppener">Base de Dados</a></li>
      </ul>
	</nav>
  </header>
    
  
</template>

<script>

export default {
  name: 'Navbar',
  props: {
    noticias: String,
    contactos: String,
  },
  methods: {
    scrollToElement(destination) {
      const element = document.querySelector(destination);
      
      if (element) {
        element.scrollIntoView({behavior: 'smooth'});
      }
    },
  }
  
};
</script>

<style lang="scss">
.header {
  position: absolute;
	z-index: 10;
	width: 100%;
	opacity: 1;
	color: #fff;
	padding: 20px 100px 0;
  #nav {
    display: flex;
    justify-content: space-around;
    .logo {
      a {
        opacity: 1;
      }
      svg {
        position: absolute;
        top: 25px;
        left: 100px;
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
          opacity: 0.75;

          &:hover {
            opacity: 1;
          }
        }  

        .activeNavLink {
            border-bottom: 1px solid black;
          }
      }
    }
  }
}
</style>