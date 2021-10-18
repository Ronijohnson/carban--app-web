<template>
  <div class="for">

    <slider />
    <conceptproduction id="scrolled" />
    <development id="scrolldev" />
    <demoevloution />
    <datamanegement id="datamanage" />
    <marketing />
    <llinkdindemo />
    <integration />
    <bottomside />

  </div>
</template>

 

<script>
import slider from "./slider"
import conceptproduction from "./conceptproduction"
import development from "./development"
import demoevloution  from "./demoevloution"
import datamanegement  from "./datamanegement"
import marketing from "./marketing"
import llinkdindemo from "./llinkdindemo"
import integration from "./integration"
import bottomside from "./bottomside"
export default {
  name: "About",
  props: {
    msg: String,
  },
  data() {
    return {
      test: this.$route.params.conceptproduction,
      
    };
  },
  
  components:
  { slider,
  conceptproduction,
  development,
  demoevloution,
  datamanegement,
  marketing,
  llinkdindemo,
  integration,
  bottomside,

  },
      methods: {
           scrolled(){
          document.getElementById("scrolled").scrollIntoView({behavior:'smooth'});;
   },
         scrolldev(){
               document.getElementById("scrolldev").scrollIntoView({behavior:'smooth'});;
         },
          datamanage(){
               document.getElementById("datamanage").scrollIntoView({behavior:'smooth'});;
         },
   },
   mounted(){
   console.log(this.test)

     if(this.test == 'development') {
        this.scrolldev();
      } else if(this.test == 'conceptproduction'){
        this.scrolled();
      }else if(this.test == 'datamanagment'){
      this.datamanage();
      }
     
     
   }
};
</script>

<style  src="./About.css" scoped >
</style>

