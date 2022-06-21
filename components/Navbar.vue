<template>
  <div class="navbarr">
    <div class="container pt-3 pb-3">
      <div class="row">
        <div class="col-3">
          <a class="text-light nav_header">Shoe Cleaning</a>
        </div>
        <div class="col-7">
          <ul class="nav justify-content-end">
            <li class="nav-item">
              <a class="nav-link text-light" id="nav_text" href="#">HOME</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" id="nav_text" href="#">SERVICES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" id="nav_text" href="#">ABOUT</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" id="nav_text" href="#"
                >TESTIMONIAL</a
              >
            </li>
          </ul>
        </div>
        <div class="col-2 text-end">
          <a id="login-button" class="btn btn-light" href="/user/login"
            >Login</a
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
