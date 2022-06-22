<template>
  <div class="grid-container">
    <Auth />
    <Nuxt />
  </div>
</template>

<script>
import Auth from "~/components/user/Auth.vue";
export default {
  name: "auth",
  components: { Auth },
};
</script>

<style>
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

body {
  height: 100%;
  overflow-x: hidden;
}

.grid-container {
  height: 100%;
  display: grid;
  grid-template-columns: 50% 50%;
}

/* Konten Kiri */
#grid-left {
  height: 100%;
  background-color: var(--primary);
}

#grid-right {
  height: 100%;
}

#text-kiri {
  font-size: 24px;
  font-weight: var(--semi-bold);
  color: var(--primary-text);
}

#slip-color {
  color: var(--slip-color1);
}
/* Konten Kiri */

/* both */
#link-page {
  text-decoration: none;
}
/* both */
</style>
