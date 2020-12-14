<template>
  <div>
    <div class="container-fluid" style="text-align: center; margin: 3%">
      <h2>NOTICIAS</h2>
    </div>

    <div class="row" bg>
      <div
        class="col newsColum"
      >
        <h3>Noticia 1</h3>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col newsColum"
      >
        <h3>Noticia 2</h3>

        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>

    <div class="row" bg>
      <div
        class="col newsColum"
      >
        <h3>Noticia 3</h3>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
      <div
        class="col newsColum"
      >
        <h3>Noticia 4</h3>
        <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
      </div>
    </div>
  </div>
</template>

<script>
import "../assets/css/noticias.css";

export default {
  name: "Noticias",
  props: ["news"],
};
</script>