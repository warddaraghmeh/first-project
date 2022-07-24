<template>
<div >
     
<img :src="photo" alt="" class="logo"/>
<span > ward </span>
     
 </div>
  
</template>

<script lang="ts">
import { defineComponent } from "vue";
import photo from "../assets/.as.png"
export default defineComponent ({
  name: "imge",
  components: {},


  setup() {


    return {photo};
  },
});
</script>

<style>
.logo {
    width:50px;
    height:50px;
 }
 

</style>