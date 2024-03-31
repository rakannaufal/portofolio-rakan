<template>
  <div>
    <section class="project" id="project">
      <h2><span>Project</span>Saya</h2>
      <p>Berikut adalah beberapa project yang pernah saya kerjakan.</p>
      <div class="row">
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/2.png" />
          </div>
          <div class="project-content">
            <h3>Aplikasi Kopi Sejuk</h3>
          </div>
        </div>
        <div class="project-card">
          <div class="project-image">
            <img src="../assets/img/projects/4.png" />
          </div>
          <div class="project-content">
            <h3>Aplikasi Laundry Cepat</h3>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.project .row {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap: 1.5rem;
  margin-top: 4rem;
}

.project .project-card {
  text-align: center;
  padding: 2rem;
}

.project .project-icon {
  display: flex;
  justify-content: center;
  gap: 0.5rem;
}
.project .project-icon a {
  width: 4rem;
  height: 4rem;
  color: #fff;
  margin: 0.3rem;
  border: 1px solid #666;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.project .project-icon a:hover {
  background-color: var(--primary);
  border: 1px solid var(--primary);
}
.project .project-image img {
  height: 25rem;
}

.project h3 {
  margin-top: 1rem;
}
.project .project-star {
  font-size: 1.7rem;
  padding: 0.8rem;
  color: var(--primary);
}
.project .project-star .star {
  fill: var(--primary);
}
.project .project-price {
  font-size: 1.3rem;
  font-weight: bold;
}
</style>
