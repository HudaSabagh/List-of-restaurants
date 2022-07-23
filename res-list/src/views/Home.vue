<template>
  <div class="home">
    <Nav></Nav>
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from "@/components/Nav.vue";

export default {
  name: "nav",
  components: {
    Nav,
  },
};
</script>
