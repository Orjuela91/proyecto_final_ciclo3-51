<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>OUR TEAM</h2>
    </div>

    <div class="row" bg>
      <div
        class="col teamColum"
      >
        <h3 style="text-align: center">Homer Simpson</h3>
        <img
          class="img-fluid mx-auto d-block teamImg"
          src="../assets/homero.jpg"
          alt="Chania"
        />
        <p>
          Some text about me in culpa qui officia deserunt mollit anim sdjd kdkd
          ididi dididi dodod dododof f seds
        </p>
      </div>
      <div
        class="col teamColum"
      >
        <h3 style="text-align: center">Marge Simpsom</h3>
        <img
          class="img-fluid mx-auto d-block teamImg"
          src="../assets/marge.jpg"
          alt="Chania"
        />
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col teamColum"
      >
        <h3 style="text-align: center">Bart Simpsom</h3>
        <img
          class="img-fluid mx-auto d-block teamImg"
          src="../assets/bart.png"
          alt="Chania"
        />
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col teamColum"
      >
        <h3 style="text-align: center">Lisa Simpsom</h3>
        <img
          class="img-fluid mx-auto d-block teamImg"
          src="../assets/lisa.png"
          alt="Chania"
        />
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col teamColum"
      >
        <h3 style="text-align: center">Maggie Simpson</h3>
        <img
          class="img-fluid mx-auto d-block teamImg"
          src="../assets/magie.gif"
          alt="Chania"
        />
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>
  </div>
</template>

<script>
import "../assets/css/equipo.css";

export default {
  name: "Equipo",
  props: ["members"],
};
</script>