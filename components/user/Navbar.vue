<template>
  <nav class="navbar navbar-expand-lg navbarr">
    <div class="container">
      <nuxt-link class="navbar-brand text-light" id="nav_header" to="#"
        >Shoe Cleaning</nuxt-link
      >
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto pe-lg-5 mb-2 mb-lg-0">
          <li class="nav-item">
            <nuxt-link class="nav-link pe-lg-5 text-light" id="nav_text" to="#"
              >HOME</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link pe-lg-5 text-light" id="nav_text" to="#"
              >SERVICES</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link pe-lg-5 text-light" id="nav_text" to="#"
              >ABOUT</nuxt-link
            >
          </li>
          <li class="nav-item">
            <nuxt-link class="nav-link pe-lg-5 text-light" id="nav_text" to="#"
              >TESTIMONIAL</nuxt-link
            >
          </li>
        </ul>
        <form action="/user/login" class="d-flex">
          <button class="btn btn-light" id="login-button" type="submit">
            Login
          </button>
        </form>
      </div>
    </div>
  </nav>
</template>

<style>
/* navbar */
.navbarr {
  background-color: var(--primary);
}

#nav_header {
  font-family: "Londrina Solid", cursive;
  font-size: 28px;
  text-decoration: none;
}

#nav_text {
  font-weight: var(--semi-bold);
  font-size: 18px;
}

#login-button {
  color: var(--primary);
  font-weight: var(--semi-bold);
  font-size: 18px;
}
/* navbar */

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
</style>
