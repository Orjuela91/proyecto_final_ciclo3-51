<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>OUR TEAM</h2>
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
        <h3 style="text-align: center">Homer Simpson</h3>
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/homero.jpg"
          alt="Chania"
          style="height: 200px"
        />
        <p>
          Some text about me in culpa qui officia deserunt mollit anim sdjd kdkd
          ididi dididi dodod dododof f seds
        </p>
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
        <h3 style="text-align: center">Marge Simpsom</h3>
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/marge.jpg"
          alt="Chania"
          style="height: 200px"
        />
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
        <h3 style="text-align: center">Bart Simpsom</h3>
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/bart.png"
          alt="Chania"
          style="height: 200px"
        />
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
        <h3 style="text-align: center">Lisa Simpsom</h3>
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/lisa.png"
          alt="Chania"
          style="height: 200px"
        />
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
        <h3 style="text-align: center">Maggie Simpson</h3>
        <img
          class="img-fluid mx-auto d-block"
          src="../assets/magie.gif"
          alt="Chania"
          style="height: 200px"
        />
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Equipo",
  props: ["members"],
};
</script>