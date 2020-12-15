<template>
  <div class="col col-lg-5 newsColum">
    <h3>{{ this.title }}</h3>
    <p>{{ this.description }}</p>
    <span>Ver fuente <a :href="this.url" target="blank">aquí </a></span>
  </div>
</template>
<script>
export default {
  name: "NewsCard",
  props: ["News"],
  data() {
    return {
      title: "",
      description: "",
      url: "#",
    };
  },
  created() {
    this.title = this.News.title;
    this.description = this.News.description;
    this.url = this.News.url;
  },
};
</script>
