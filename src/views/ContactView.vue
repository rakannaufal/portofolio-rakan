<template>
  <div>
    <section id="contact" class="contact">
      <h2><span>Kontak</span>Saya</h2>
      <p>Tertarik untuk menghire saya? silahkan hubungi saya.</p>
      <p>Mari bekerja sama!</p>
      <div class="row">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d426.72547813403713!2d101.47943639454036!3d0.5303881054663027!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sid!2sid!4v1700313128134!5m2!1sid!2sid"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          class="map"
        >
        </iframe>
        <form action="">
          <div class="input-group">
            <i data-feather="user"></i>
            <input type="text" placeholder="Nama" />
          </div>
          <div class="input-group">
            <i data-feather="mail"></i>
            <input type="text" placeholder="Email" />
          </div>
          <div class="input-group">
            <i data-feather="phone"></i>
            <input type="text" placeholder="Handphone" />
          </div>
          <button type="submit" class="btn">Kirim Pesan</button>
        </form>
      </div>
    </section>
  </div>
</template>

<style scoped>
.contact .row {
  display: flex;
  margin-top: 2rem;
  background-color: #222;
}

.contact .row .map {
  flex: 1 1 45rem;
  width: 100%;
  object-fit: cover;
}
.contact .row form {
  flex: 1 1 45rem;
  padding: 5rem 2rem;
  text-align: center;
}

.contact .row form .input-group {
  display: flex;
  align-items: center;
  margin-top: 2rem;
  background-color: var(--bg);
  border: 1px solid #eee;
  border-radius: 4px;
  padding-left: 2rem;
}

.contact .row form .input-group input {
  width: 100%;
  padding: 1rem;
  font-size: 1.7rem;
  background: none;
  color: #fff;
}

.contact .row form .btn {
  margin-top: 3rem;
  display: inline-block;
  padding: 1rem 3rem;
  font-size: 1.7rem;
  color: #fff;
  background-color: var(--primary);
  cursor: pointer;
  border-radius: 4px;
}
</style>
