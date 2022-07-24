<script  lang="ts">
import { defineComponent } from "vue";
 
import baseHeader from './components/base-header.vue';

export default defineComponent({
  name: "app",
  components: {baseHeader},


  setup() {



    return {

    };
  },
});

</script>

<template>
<base-header></base-header>
</template>

<style scoped>
</style>
