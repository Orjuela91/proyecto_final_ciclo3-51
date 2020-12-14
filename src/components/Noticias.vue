<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>NOTICIAS</h2>
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
        <h3>Noticia 1</h3>
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
        <h3>Noticia 2</h3>

        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>

    <div class="row" bg>
      <div
        class="col"
        style="
          background-color: lavender;
          margin-left: 1%;
          margin-right: 0.5%;
          margin-top: 0.5%;
        "
      >
        <h3>Noticia 3</h3>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col"
        style="
          background-color: lavender;
          margin-left: 0.5%;
          margin-right: 1%;
          margin-top: 0.5%;
        "
      >
        <h3>Noticia 4</h3>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Noticias",
  props: ["news"],
};
</script>