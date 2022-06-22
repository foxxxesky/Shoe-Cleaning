<template>
  <!-- Right Content -->
  <section id="grid-right">
    <div class="row justify-content-center pt-5">
      <div class="col-10 pt-5">
        <h4 id="text-registrasi" class="pb-4">Registrasi</h4>
      </div>
    </div>

    <!-- Form -->
    <form action="#" method="POST">
      <div class="fomr-floating">
        <div class="row justify-content-center">
          <!-- Layout kiri -->
          <div class="col-5">
            <!-- Fname -->
            <div class="mb-4">
              <label for="Fname" id="form-text" class="form-label"
                >Nama Depan</label
              >
              <input type="text" class="form-control" name="first_name" />
            </div>

            <!-- No HP -->
            <div class="mb-4">
              <label for="nohp" id="form-text" class="form-label"
                >Nomor Telepon</label
              >
              <input type="text" class="form-control" name="no_hp" />
            </div>

            <!-- Password -->
            <div class="mb-4">
              <label for="password" id="form-text" class="form-label"
                >Kata Sandi</label
              >
              <input type="password" class="form-control" name="password" />
            </div>
          </div>

          <!-- Layout Kanan -->
          <div class="col-5">
            <!-- Lname -->
            <div class="mb-4">
              <label for="Lname" id="form-text" class="form-label"
                >Nama Belakang</label
              >
              <input type="text" class="form-control" name="last_name" />
            </div>

            <!-- Email -->
            <div class="mb-4">
              <label for="email" id="form-text" class="form-label">Email</label>
              <input type="email" class="form-control" name="email" />
            </div>

            <!-- Confirm -->
            <div class="mb-4">
              <label
                for="password_confirmation"
                id="form-text"
                class="form-label"
                >Konfirmasi Kata Sandi</label
              >
              <input
                type="password"
                class="form-control"
                name="password_confirmation"
              />
            </div>
          </div>
        </div>

        <div class="row justify-content-center">
          <!-- checkbox -->
          <div class="col-10">
            <div class="form-check">
              <input
                type="checkbox"
                class="form-check-input"
                name="setujuemail"
              />
              <label id="checkbox-text" class="form-check-label" for="remember"
                >Ya, Saya ingin menerima email
                <span id="slip-color2">ShoeCleaning</span></label
              >
            </div>

            <div class="form-check pb-3">
              <input
                type="checkbox"
                class="form-check-input"
                name="setujukebijakan"
              />
              <label id="checkbox-text" class="form-check-label" for="remember"
                >Saya setuju dengan semua
                <span id="slip-color2">Kebijakan Privasi</span></label
              >
            </div>

            <!-- Button -->
            <div class="pb-3">
              <button
                id="register-button"
                type="submit"
                name="Masuk"
                class="btn btn-primary"
                style="width: 10rem"
              >
                Buat Akun
              </button>
            </div>

            <div>
              <p id="link-text-login">
                Sudah punya akun?
                <nuxt-link id="link-page" to="/user/login">Masuk</nuxt-link>
              </p>
            </div>
          </div>
        </div>
      </div>
    </form>
    <!-- Form -->
  </section>
  <!-- Right Content -->
</template>

<script>
export default {
  layout: "auth",
  head() {
    return {
      title: "Register",
    };
  },
};
</script>

<style>
#text-registrasi {
  font-size: 36px;
  font-weight: var(--bold);
  color: var(--primary-text);
}

#checkbox-text {
  font-size: 11px;
  color: var(--primary-text);
}

#checkbox-text {
  font-size: 14px;
  font-weight: var(--medium);
  color: var(--secondary-text);
}

#checkbox-text-login {
  font-size: 14px;
  font-weight: var(--medium);
  color: var(--primary-text);
}

#slip-color2 {
  color: var(--slip-color2);
}

#register-button {
  font-size: 20px;
  font-weight: var(--semi-bold);
}

#link-text-login {
  font-size: 14px;
  font-weight: var(--medium);
  color: var(--primary-text);
}
</style>
