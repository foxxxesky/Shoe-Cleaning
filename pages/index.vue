<template>
  <div class="content">
    <!-- Jumbotron -->
    <div class="jumbotron">
      <div class="container pt-5 pb-5">
        <div class="row">
          <div class="col-7">
            <div class="col-kiri pb-2">
              <h4 id="text-jumbotron">
                Shoe Cleaning Siap Membersihkan Sepatu Anda!
              </h4>
              <p id="desc-jumbotron">
                Percayakan sepatu kesukaan anda kepada kami!
              </p>
              <nuxt-link id="button-jumbotron" class="btn btn-light" to="#"
                >Bersihkan Sekarang!</nuxt-link
              >
            </div>
          </div>
          <div class="col-5">
            <img id="img-jumbotron" src="images/char.png" alt="" />
          </div>
        </div>
      </div>
    </div>
    <!-- Jumbotron -->

    <!-- Layanan -->
    <div class="container">
      <h4 class="text-center pt-5" id="text-layanankami">Layanan Kami</h4>
    </div>
    <!-- Layanan -->
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "Shoe Cleaning",
    };
  },
};
</script>

<style>
.jumbotron {
  background-color: var(--primary);
}

.col-kiri {
  padding-top: 80px;
}

#text-jumbotron {
  font-size: 38px;
  font-weight: var(--semi-bold);
  color: var(--white);
}

#desc-jumbotron {
  font-size: 14px;
  font-weight: var(--medium);
  color: var(--white);
}

#img-jumbotron {
  position: absolute;
  height: 400px;
}

#button-jumbotron {
  font-size: 20px;
  font-weight: var(--semi-bold);
  color: var(--primary);
}
</style>
