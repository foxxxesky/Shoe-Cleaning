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
