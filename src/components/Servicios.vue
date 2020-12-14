<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>NUESTROS SERVICIOS</h2>
    </div>

    <div class="row" bg>
      <div
        class="col"
        style="
          background-color: lavender;
          margin-left: 1%;
          margin-right: 0.5%;
          margin-bottom: 0.5%;
        "
      >
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/pyton.png"
          alt="Chania"
          style="height: 200px"
        />
        <h5>PYTHON</h5>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col"
        style="
          background-color: lavender;
          margin-left: 0.5%;
          margin-right: 1%;
          margin-bottom: 0.5%;
        "
      >
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/java.png"
          alt="Chania"
          style="height: 200px"
        />
        <h5>JAVA</h5>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col"
        style="
          background-color: lavender;
          margin-left: 0.5%;
          margin-right: 1%;
          margin-bottom: 0.5%;
        "
      >
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/sql.png"
          alt="Chania"
          style="height: 200px"
        />
        <h5>SQL</h5>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Servicios",
  props: ["services"],
};
</script>