<template>
  <div class="col serviceColum">
    <img
      class="img-fluid mx-auto d-block serviceImg"
      :src="this.image"
      alt="Chania"
    />
    <h5>{{this.name}}</h5>
    <p>{{this.description}}</p>
  </div>
</template>

<script>
export default {
  name: "ServiceCard",
  props: ["service"],
  data() {
      return{
          name: "",
          description: "",
          image: ""
      }
  },
  created(){
    this.name = this.service.name;
    this.description = this.service.description;
    this.image = this.service.image;
  }

};
</script>