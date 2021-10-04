<template>
  <div>

    <slider />
    <conceptproduction />
    <development />
    <demoevloution />
    <datamanegement />
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
  
 
};
</script>

<style  src="./About.css" scoped >
</style>

