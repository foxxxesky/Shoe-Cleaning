<template>
  <div>
    <Navbar />
    <Home />
    <Nuxt />
  </div>
</template>

<script>
import Navbar from "~/components/user/Navbar.vue";
import Home from "~/components/user/Home.vue";
export default {
  name: "default",
  components: { Navbar, Home },
};
</script>
