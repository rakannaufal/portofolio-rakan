<template>
  <div>
    <section id="services" class="services">
      <h2><span>Services</span>Saya</h2>
      <p>
        Berikut adalah beberapa Bahasa Pemrograman dan Framework yang digunakan
        dalam membuat project.
      </p>
      <div class="row">
        <div class="services-card">
          <img
            src="../assets/img/menu/1.png"
            alt="Kopi Manis"
            class="services-card-image"
          />
          <h3 class="services-card-title">Laravel</h3>
        </div>
        <div class="services-card">
          <img
            src="../assets/img/menu/2.png"
            alt="Kopi Manis"
            class="services-card-image"
          />
          <h3 class="services-card-title">Vue.js</h3>
        </div>
        <div class="services-card">
          <img
            src="../assets/img/menu/3.png"
            alt="Kopi Manis"
            class="services-card-image"
          />
          <h3 class="services-card-title">PHP</h3>
        </div>
        <div class="services-card">
          <img
            src="../assets/img/menu/4.png"
            alt="Kopi Manis"
            class="services-card-image"
          />
          <h3 class="services-card-title">Bootstrap</h3>
        </div>
        <div class="services-card">
          <img
            src="../assets/img/menu/5.png"
            alt="Kopi Manis"
            class="services-card-image"
          />
          <h3 class="services-card-title">JavaScript</h3>
        </div>
        <div class="services-card">
          <img
            src="../assets/img/menu/6.png"
            alt="Kopi Manis"
            class="services-card-image"
          />
          <h3 class="services-card-title">Java</h3>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.services .row {
  display: flex;
  flex-wrap: wrap;
  margin-top: 5rem;
  justify-content: center;
}

.services .row .services-card {
  text-align: center;
  padding-bottom: 4rem;
}

.services .row .services-card img {
  border-radius: 50%;
  width: 80%;
}

.services .row .services-card .services-card-title {
  margin: 1.5rem auto 0.5rem;
  font-size: 1.4rem;
}
</style>
