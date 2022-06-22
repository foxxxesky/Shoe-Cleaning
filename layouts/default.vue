<template>
  <div>
    <Navbar />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/user/Navbar.vue";
import Footer from "~/components/user/Footer.vue";
export default {
  name: "default",
  components: { Navbar, Footer },
};
</script>
