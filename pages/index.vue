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
              <nuxt-link
                id="button-jumbotron"
                class="btn btn-light"
                to="user/service"
                >Bersihkan Sekarang!</nuxt-link
              >
            </div>
          </div>
          <div class="col-5">
            <img id="img-jumbotron" src="~static/images/char.png" alt="" />
          </div>
        </div>
      </div>
    </div>
    <!-- Jumbotron -->

    <!-- Layanan -->
    <div class="container">
      <h4 class="text-center pt-5" id="text-layanankami">Layanan Kami</h4>
    </div>
    <div class="pt-2">
      <hr />
    </div>
    <p class="text-center pt-2 pb-2" id="desc-layanan">
      Kami telah mencuci lebih dari 1000 pasang sepatu, dan akan terus
      bertambah... <br />
      Berikut jasa yang kami tawarkan
    </p>

    <div class="container pb-5">
      <div class="row">
        <div class="col-3" v-for="product in service" :key="service.id">
          <img
            :src="require(`~/static/images/${product.small_img}`)"
            id="img_layanan"
            alt="img"
          />
          <h5 class="pt-3 text-center" id="item-layanan">
            {{ product.title }}
          </h5>
        </div>
      </div>
    </div>
    <!-- Layanan -->
  </div>
</template>

<script>
import { products } from "@/store/products.js";
export default {
  head() {
    return {
      title: "Shoe Cleaning",
    };
  },
  data() {
    return {
      service: products,
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

hr {
  width: 100px;
  margin: auto;
  height: 4px;
  color: var(--primary);
  background-color: var(--primary);
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

/* Layanan */
#text-layanankami {
  font-size: 36px;
  font-weight: 700;
  color: #504a4a;
}

#desc-layanan {
  font-size: 16px;
  color: #504a4a;
}

#img_layanan {
  height: 263px;
}
/* Layanan */
</style>
