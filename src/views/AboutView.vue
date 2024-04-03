<template>
  <div>
    <section id="about" class="about">
      <h2><span>About</span>Saya</h2>
      <div class="row">
        <div class="about-img">
          <img
            src="../assets/img/about.jpg"
            width="640px"
            height="450px"
            alt=""
          />
        </div>
        <div class="content">
          <h3>Biodata saya</h3>
          <p>
            Perkenalkan saya M Rakan Naufal lahir di Pekanbaru pada tanggal 11
            Juni 2003, saat ini sedang menempuh pendidikan di Universitas Islam
            Riau jurusan Teknik Informatika.
          </p>
          <p>
            Sebelumnya saya bersekolah di Man 1 Pekanbaru.Saya memiliki
            tertarikan pada dunia Coding saat kelas 9 SMP,dimana saya selalu
            mencari Film dan Informasi seputar Coding.
          </p>
          <p>
            Pada kelas 10 MAN saya mulai serius dalam mendalami Coding dimulai
            dari belajar HTML,CSS,PHP dan dilanjutkan belajar Framework seperti
            Laravel dan Bootstrap.Adapun web saya buat seperti Kas Kelas,Online
            Shop yang mana saat itu masih sekedar web biasa.
          </p>
          <p>
            Saat ini saya ingin memperdalam lagi dunia Coding terutama pada Web
            Developer supaya bisa menjadi Programmer yang sukses.
          </p>
        </div>
        <div class="content">
          <h3>Kenapa hire saya?</h3>
          <p>
            Saya memiliki kombinasi unik antara keterampilan teknis dan kreatif
            yang memungkinkan saya untuk menghasilkan website yang tidak hanya
            indah, tetapi juga berkinerja tinggi. Saya berpengalaman dalam
            berbagai platform dan teknologi web, termasuk:
          </p>
          <p>HTML CSS JavaScript SEO Pemrograman Back-end</p>
          <p>
            Saya juga memiliki pengetahuan dan pengalaman dalam desain web,
            branding, dan marketing. Saya selalu mengikuti perkembangan terbaru
            dalam teknologi web dan selalu berusaha untuk meningkatkan
            keterampilan saya.
          </p>
          <p>
            Saya bukan hanya seorang web developer. Saya akan bekerja sama
            dengan Anda untuk memahami kebutuhan Anda dan mengembangkan website
            yang sesuai dengan anggaran dan timeline Anda. Saya juga akan
            memberikan support dan maintenance setelah website Anda diluncurkan.
          </p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.about .row {
  display: flex;
}
.about .row .about-img {
  flex: 1 1 45rem;
}
.about .row .about-img img {
  width: 100%;
}

.about .row .content {
  flex: 1 1 30rem;
  padding: 0 1rem;
}
.about .row .content h3 {
  font-size: 1rem;
  margin-bottom: 1rem;
  color: var(--primary);
}

.about .content p {
  color: #000000;
  margin-bottom: 0.8rem;
  font-weight: 700;
  font-size: 0.8rem;
  line-height: 1.6rem;
}
</style>
