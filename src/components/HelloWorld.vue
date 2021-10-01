<template>
  <div>
   <!-- <header /> -->
    <dailersoftwear />
    <br />
    <br />
    <powerdial />
    <appbycarbanweb />
    <recommended />
    <bottom />
  </div>
</template>

<script>
// import header from "./header"
import dailersoftwear from "./dailersoftwear";
import powerdial from "./powerdial";
import appbycarbanweb from "./appbycarbanweb";
import recommended from "./recommended";
import bottom from "./bottom";
export default {
  name: "HelloWorld",
  components: {
    dailersoftwear,
    powerdial,
    appbycarbanweb,
    recommended,
    bottom,
    // header,
  },
  props: {
    msg: String,
  },
  mounted() {
    console.log(this.$route);
  },
};
</script>

<style  src="./Hello.css" scoped >

</style>


































































  
