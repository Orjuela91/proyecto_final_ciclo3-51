<template>
  <div class="container-fluid bg-white">
    <nav
      class="navbar navbar-expand-sm bg-dark navbar-dark justify-content-end"
    >
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#">Inicio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Servicios</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Noticas</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">our Team</a>
        </li>
      </ul>
    </nav>

    <Slideshow/>
    
    <Servicios/>

    <Noticias/>

    <Equipo/>

    <div class="container-fluid">
      <div class="row justify-content-center mb-5">
        <div class="col mt-5" v-for="(miembro, index) of Team" :key="index">
          <team-card :member="miembro" > </team-card>
        </div>
      </div>
    </div>
    
    <Footer/>
    
  </div>
</template>

<script>
import TeamCard from "./components/TeamCard.vue";
import Slideshow from "./components/Slideshow.vue";
import Servicios from "./components/Servicios.vue";
import Noticias from "./components/Noticias.vue";
import Equipo from "./components/Equipo.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    TeamCard: TeamCard,
    Slideshow: Slideshow,
    Servicios: Servicios,
    Noticias: Noticias,
    Equipo: Equipo,
    Footer: Footer
  },
  methods: {},
  data() {
    return {
       Team:[
        {
        codigo : 1 ,
        nombre : 'Jurgen Orjuela' ,
        descripcion : 'leer, videojuegos, estudiar.' ,
        rol : 'Desarrollador de sofware' ,
        image : 'https://i.imgur.com/XuOvYfE.jpg'
        },
        {
        codigo : 2 ,
        nombre : 'David Turizo' ,
        descripcion : 'Leer, Musica,Tocar la guitarra.' ,
        rol : 'Ingeniero Electronico' ,
        image : 'https://i.imgur.com/j2eUbQM.jpg'
        },
        {
        codigo : 3 ,
        nombre : 'William Vargas' ,
        descripcion : 'Ver series.' ,
        rol : 'Estudiante de Ingenieria Mecatronica' ,
        image : 'https://i.imgur.com/jE7KCYY.jpg'
        },
        {
        codigo : 4 ,
        nombre : 'Daniela Laverde' ,
        descripcion : 'Leer,Crear,Ver series.' ,
        rol : 'Psicóloga' ,
        image : 'https://i.imgur.com/wPcCF2m.jpg'
        },
        {
        codigo : 5 ,
        nombre : 'Marisol Osma' ,
        descripcion : 'Dibujar,Tocar el violin.' ,
        rol : 'Estudiante de musica' ,
        image : 'https://i.imgur.com/OInkAD8.jpg'
        }
      ]
    };
  },
};
</script>

<style scoped>
</style>

