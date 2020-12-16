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
    return {};
  },
};
</script>

<style scoped>
</style>

