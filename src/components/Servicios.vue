<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>NUESTROS SERVICIOS</h2>
    </div>

    <div class="row" bg>
      <div
        class="col serviceColum"
      >
        <img
          class="img-fluid mx-auto d-block serviceImg"
          src="../assets/pyton.png"
          alt="Chania"
        />
        <h5>PYTHON</h5>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col serviceColum"
      >
        <img
          class="img-fluid mx-auto d-block serviceImg"
          src="../assets/java.png"
          alt="Chania"
        />
        <h5>JAVA</h5>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
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
import "../assets/css/servicios.css";

export default {
  name: "Servicios",
  props: ["services"],
};
</script>