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
  head() {
    return {
      link: [
        {
          rel: "icon",
          href: "~/static/images/char.png",
        },
      ],
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Londrina+Solid&display=swap");
@import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.3/font/bootstrap-icons.css");

:root {
  /* Color */
  --primary: #8f5bd8;
  --white: #ffffff;
  --primary-text: #504a4a;
  --secondary-text: #a5a5a5;
  --slip-color1: #98cdc8;
  --slip-color2: #4461f2;
  --warning: #ffc107;

  /* Font-Weight */
  --medium: 500;
  --semi-bold: 600;
  --bold: 700;
}

* {
  font-family: "Inter", sans-serif;
}
</style>
