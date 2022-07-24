<script lang="ts">
import { defineComponent } from "vue";
import imge from "./imge.vue"
import botton from "./botton.vue"
export default defineComponent({
  name: "baseHeader",
  components: {
    imge,botton
  },


  setup() {



    return {};
  },
});
</script>

<template>
<div class="tt">
 <botton></botton>
<imge></imge>   
    
</div>

</template>


<style scoped>
 .tt
{
    display: flex;
}

</style>
