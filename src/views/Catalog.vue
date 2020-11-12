<template>
  <div class="catalog">
    
    <HelloWorld />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Catalog",
  components: {
    HelloWorld
  }
};
</script>