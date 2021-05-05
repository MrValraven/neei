<template>
  <Navbar />
   <section class="hero">
      <div class="heroContent">
        <div class="textArea">
          <h1 class="slogan">Núcleo de Estudantes de<br>Engenharia Informática</h1>
          <p class="heroText">O NEEI é o núcleo de estudantes de engenharia Informática da universidade de Évora, que tem como objectivo apoiar os alunos do departamento de informática da Universidade de Évora</p>
          <div class="buttons">
            <button class="vantagens">Descobre as vantagens</button>
            <button class="socio">Faz-te Sócio!</button>
          </div>
        </div>
        <img class="heroImage" src="@/assets/digitalNomad.svg" alt="">
      </div>
    </section>
    <section class="ourWork">
      <div class="ativismo">
        <img src="@/assets/placeholder.jpg" alt="">
        <div class="text">
          <h1>we do stuff</h1>
          <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dicta quis officiis praesentium iure quisquam recusandae inventore fuga quia sapiente libero?</p>
        </div>
      </div>
    </section>
    <section class="recrutamento">
      <div class="aboutUs">
        <div class="text">
          <h1>Mas quem é a AAUE?</h1>
          <p>Somos estudantes, tal como tu, que  trabalham, lutam e dão a cara. A AAUE é quem tenta encontrar a melhor solução para a maioria dos estudantes</p>
          <p>Ao nível interno a AAUÉ tem assento no Senado Universitário, no Conselho de Acção Social, no Conselho de Avaliação, no Conselho Consultivo do Fundo de Acção Social da UÉ, no Gabinete para a Promoção do Sucesso Académico, no Conselho Desportivo da UÉ, no Conselho da Fundação Luís de Molina e na Assembleia de Representantes.</p>
          <p>Ao nível externo a AAUÉ desempenha um papel político junto das outras associações congéneres, no Ministério da Educação e Ciência e está representada em órgãos estatais e regionais. Faz ainda parte do Fórum Académico para a Informação e Representação Externa (FAIRe) e na Federação Académica do Desporto Universitário (FADU), na qual é membro fundador.</p>
          <p>A AAUÉ faz ainda parte do Conselho Municipal de Juventude, do Conselho Consultivo Regional do IPDJ e do Conselho Municipal de Educação.</p>
          <p>Para além do trabalho político a AAUÉ promove actividades culturais e desportivas e presta aos seus membros, os estudantes, serviços variados, desde o lazer e a informação à formação extra-curricular.</p>
        </div>
       <img src="@/assets/placeholder.jpg" alt="">
      </div>
    </section>
    <section class="plataformas">
      <h1>Plataformas</h1>
      <p>De forma a ajudar os estudantes da Universidade de Évora, a AAUE disponibiliza as seguintes plataformas de interesse dos estudantes que podem ser acedidas através das ligações:</p>
    </section>
    <section class="noticias">
      <div class="noticiasPreview">
        <h1>Notícias</h1>
        <h2>Últimas noticias da Associação Académica da Universidade de Évora. </h2>
      </div>
      
    </section>
    <Footer />

  
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Navbar,
    Footer
  },
  created() {
    window.addEventListener('scroll', this.handleScroll);
    this.handleResize();
    window.addEventListener('resize', this.handleResize);
  },
  unmounted() {
    window.removeEventListener('scroll', this.handleScroll);
    window.removeEventListener('resize', this.handleResize);
  },
   methods: {
    scrollToElement(destination) {
      const element = document.querySelector(destination);
      if (element) {
        element.scrollIntoView({behavior: 'smooth'});
      }
    },
    getImgURL(image) {
        return require('../assets/' + image);
    },
    handleScroll () {
      window.pageYOffset >= 250 ? this.isAtTop = false : this.isAtTop = true;
    },
    handleResize () {
      this.mobileMode = window.innerWidth <= 1015;
      if(!this.mobileMode) {
        this.activatedNavbar = false;
      }
    },
  },
};
</script>

<style lang="scss" scoped>

$informaticaBlue: #1935A1;


section {
  padding: 20px;
}
.heroContent {
  height: 100vh;
  display: flex;
  justify-content: space-around;
  align-items: center;
  .textArea {
    display: flex;
    width: 50%;
    justify-content: left;
    align-items: left;
    flex-direction: column;
    .slogan {
      font-size: 3vw;
      margin: 10px 25px;
      text-transform: uppercase;
    }
    
    .heroText {
      margin: 0px 25px;
    }

    button {
      max-width: 300px;
      position: relative;
      display: inline-block;
      text-align: center;
      text-transform: uppercase; 
      padding: 15px;
      margin: 30px 25px;
      font-size: 100% + 10%;
      font-weight: 600;
      border-radius: 5px;
      border: none;
      color: $informaticaBlue;
      background-color: white;
      transition: all 0.5s;
      &::before {
        position: absolute;
        content:"";
        border-radius: 5px;
        border-top: 5px solid lighten($informaticaBlue, 5%);
        border-left: 5px solid lighten($informaticaBlue, 5%);	
        border-right: 5px solid darken($informaticaBlue, 5%);
        border-bottom: 5px solid darken($informaticaBlue, 5%);
        top: 0px;
        right: 0px;
        bottom: 0px;
        left: 0px;	
        transition: 0.5s;
      }
      &:hover {
        box-shadow: 7px 7px darken($informaticaBlue, 10%), -7px -7px lighten($informaticaBlue, 10%);
        background-color: $informaticaBlue;
        color: #f7f7f7;
        cursor: pointer;
          &::before {
          border: 0px;
        }
      }
    }
    .socio {
      background: #f7f7f7;
      color: $informaticaBlue;
    }
    .socio:hover {
      box-shadow: 7px 7px darken($informaticaBlue, 10%), -7px -7px lighten($informaticaBlue, 10%);
      background-color: $informaticaBlue;
      color: #f7f7f7;
      cursor: pointer;
    }
  }
  .heroImage {
    width: 600px;
  }
}
.ourWork {
  padding: 20px;
  height: 100vh;
  .ativismo {
    display: flex;
    img {
      margin-right: 30px;
      width: 50%
    
    }
    .text {
      display: flex;
      flex-direction: column;
      h1 {
        text-transform: uppercase;
      }
    }
  }
}
.recrutamento {
  padding: 20px;
  height: 100vh;
  .aboutUs {
    display: flex;
    img {
      margin-left: 30px;
      width: 50%
    
    }
    .text {
      display: flex;
      flex-direction: column;
      h1 {
        text-transform: uppercase;
      }
    }
  }
}
.plataformas {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  h1 {
    font-size: 80px;
  }
  .plataformaCards {
    display: flex;
  }
}
.noticias {
  h1 {
    font-size: 80px;
  }
  .noticiasPreview {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    .carrossel {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
  }
}
</style>
