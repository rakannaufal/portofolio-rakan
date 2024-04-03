<template>
  <div>
    <section class="home" id="home">
      <main class="content">
        <h1>I'm M <span> Rakan </span> Naufal</h1>
        <p>
          I am a web developer with a passion for building dinamis and
          functional websites. I am also a Informatic Engineering student,
          combining technical and creative skills.
        </p>
        <buttonc />
      </main>
    </section>
  </div>
</template>

<style scoped>
h1 {
  overflow: hidden;
  border-right: 0.15em solid var(--primary);
  white-space: nowrap;
  margin: 0 auto;
  animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from {
    width: 0;
  }
  to {
    width: 100%;
  }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: var(--primary);
  }
}
.home {
  min-height: 100vh;
  display: flex;
  align-items: center;
  background-image: url("../assets/img/header-bg.png");
  background-size: cover;
  background-position: center;
  position: relative;
}

.home::after {
  content: "";
  display: block;
  position: absolute;
  width: 100%;
  height: 30%;
  bottom: 0;
  background: linear-gradient(
    0deg,
    hsl(0, 0%, 60%) 4%,
    rgba(217, 217, 217, 0) 40%
  );
}
.home .content {
  padding: 1.4rem 7%;
  max-width: 60rem;
}
.home .content h1 {
  font-size: 4.5em;
  color: #fff;
  text-shadow: 1px 1px 3px rgba(1, 1, 3, 0.5);
  line-height: 1.2;
}

.home .content h1 span {
  color: var(--primary);
}

.home .content p {
  font-size: 1.4rem;
  margin-top: 1rem;
  line-height: 1.4;
  font-weight: 300;
  color: #fff;
  text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.5);
}
</style>

<script setup>
import buttonc from "../components/Button.vue";
</script>
