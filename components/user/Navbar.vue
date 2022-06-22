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
