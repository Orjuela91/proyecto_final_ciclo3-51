<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>NUESTROS SERVICIOS</h2>
    </div>

    <div class="row" bg>

      <ServiceCard :service="service1"/>
      <ServiceCard :service="service2"/>

      <div
        class="col serviceColum"
      >
        <img
          class="img-fluid mx-auto d-block serviceImg"
          src="../assets/sql.png"
          alt="Chania"
        />
        <h5>SQL</h5>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>
  </div>
</template>

<script>
import ServiceCard from './ServiceCard.vue';
import Python from '../assets/pyton.png';
import Java from '../assets/java.png';
import "../assets/css/servicios.css";

export default {
  name: "Servicios",
  props: ["services"],
  components: {
    ServiceCard: ServiceCard
  },
  data() {
    return {
      service1: {
        name: "Python props",
        description: "Some text about me in culpa qui officia deserunt mollit anim.. props ",
        image: Python,
      },
      service2: {
        name: "java props",
        description: "Some text about me in culpa qui officia deserunt mollit anim.. java props ",
        image: Java
      }
    };
  },
};
</script>