<template>
  <div>
    <nav class="navbar" x-data>
      <a href="#" class="navbar-logo">Rakan<span>Naufal</span>.</a>

      <div class="navbar-extra" x-data>
        <a href="#" id="hamburger-menu"
          ><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
            <path
              d="M0 96C0 78.3 14.3 64 32 64H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32C14.3 128 0 113.7 0 96zM0 256c0-17.7 14.3-32 32-32H416c17.7 0 32 14.3 32 32s-14.3 32-32 32H32c-17.7 0-32-14.3-32-32zM448 416c0 17.7-14.3 32-32 32H32c-17.7 0-32-14.3-32-32s14.3-32 32-32H416c17.7 0 32 14.3 32 32z"
            />
          </svg>
        </a>
      </div>

      <div class="navbar-nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#project">Projects</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
      </div>
      <!-- Search form end -->
    </nav>
  </div>
</template>

<style scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.4rem 7%;
  background-color: rgba(1, 1, 1, 0.8);
  border-bottom: 1px solid #513c28;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 9999;
}

.navbar .navbar-logo {
  font-size: 2rem;
  font-weight: bold;
  color: #fff;
  font-style: italic;
}

.navbar .navbar-logo span {
  color: #a6a6a6;
}

.navbar .navbar-nav {
  display: flex;
  justify-content: flex-end;
}

.navbar .navbar-nav a {
  color: #fff;
  display: inline-block;
  font-size: 1.3rem;
  margin: 0 1rem;
}

.navbar .navbar-nav a:hover {
  color: var(--primary);
}
.navbar .navbar-nav a::after {
  content: "";
  display: block;
  padding-bottom: 0.5rem;
  border-bottom: 0.1rem solid var(--primary);
  transform: scaleX(0);
  transition: 0.2s linear;
}

.navbar .navbar-nav a:hover::after {
  transform: scaleX(0.5);
}

.navbar .navbar-extra a {
  color: #fff;
  margin: 0 0.5rem;
}

.navbar .navbar-extra a:hover {
  color: var(--primary);
}

#hamburger-menu {
  display: none;
}
</style>
