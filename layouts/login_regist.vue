<template>
  <div class="grid-container">
    <Login_regist />
    <Nuxt />
  </div>
</template>

<script>
import Login_regist from "~/components/user/login_regist.vue";
export default {
  name: "login",
  components: { Login_regist },
};
</script>
