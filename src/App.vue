<script>
  import Title from "./components/AppTitle.vue";
  import Jumbotron from "./components/AppHero.vue";


  export default {
    data(){
      return{

      }
    },

    components : {
      Title,
      Jumbotron
    }
  }
</script>

<template>
  <div>
    
    <Title></Title>
    <div class="jumbo"><Jumbotron></Jumbotron></div>

  </div>
  
</template>


<style >

</style>




