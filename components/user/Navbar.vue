<template>
  <div class="navbarr">
    <div class="container pt-3 pb-3">
      <div class="row">
        <div class="col-3">
          <nuxt-link class="text-light nav_header" to="#"
            >Shoe Cleaning</nuxt-link
          >
        </div>
        <div class="col-7">
          <ul class="nav justify-content-end">
            <li class="nav-item">
              <nuxt-link class="nav-link text-light" id="nav_text" to="#"
                >HOME</nuxt-link
              >
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link text-light" id="nav_text" to="#"
                >SERVICES</nuxt-link
              >
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link text-light" id="nav_text" to="#"
                >ABOUT</nuxt-link
              >
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link text-light" id="nav_text" to="#"
                >TESTIMONIAL</nuxt-link
              >
            </li>
          </ul>
        </div>
        <div class="col-2 text-end">
          <nuxt-link id="login-button" class="btn btn-light" to="/user/login"
            >Login</nuxt-link
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>
