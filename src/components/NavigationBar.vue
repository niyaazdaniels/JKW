<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-warning bg-gradient p-3">
    <div class="container-fluid">
      <router-link class="navbar-brand" to="/">JKW</router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div
        class="collapse navbar-collapse smooth-collapse"
        id="navbarNavDropdown"
      >
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <router-link
              class="nav-link mx-2 active"
              aria-current="page"
              to="/"
              @click="closeNavbar"
              >Home</router-link
            >
          </li>
          <li class="nav-item">
            <router-link
              class="nav-link mx-2"
              to="/packages"
              @click="closeNavbar"
              >Packages</router-link
            >
          </li>
          <li class="nav-item">
            <router-link class="nav-link mx-2" to="/about" @click="closeNavbar"
              >Story</router-link
            >
          </li>
          <li class="nav-item">
            <router-link
              class="nav-link mx-2"
              to="/gallery"
              @click="closeNavbar"
              >Gallery</router-link
            >
          </li>
          <li class="nav-item">
            <router-link
              class="nav-link mx-2"
              to="/contact"
              @click="closeNavbar"
              >Contact</router-link
            >
          </li>
        </ul>
        <ul class="navbar-nav ms-auto d-none d-lg-inline-flex">
          <li class="nav-item mx-2">
            <a class="nav-link text-dark h5" href="www.facebook.com" target="_blank"
              ><i class="fa-brands fa-facebook"></i
            ></a>
          </li>
          <li class="nav-item mx-2">
            <a class="nav-link text-dark h5" href="www.twitter.com" target="_blank"
              ><i class="fa-brands fa-x-twitter"></i
            ></a>
          </li>
          <li class="nav-item mx-2">
            <a class="nav-link text-dark h5" href="www.instagram.com" target="_blank"
              ><i class="fa-brands fa-instagram"></i
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  mounted() {
    this.handleInitialNavbarState();
  },
  methods: {
    closeNavbar() {
      const navbar = document.getElementById("navbarNavDropdown");
      if (navbar.classList.contains("show")) {
        navbar.classList.add("collapsing");
        navbar.style.height = "0px";
        setTimeout(() => {
          navbar.classList.remove("show", "collapsing");
          navbar.style.height = "";
        }, 300);
      }
    },
    handleInitialNavbarState() {
      const navbar = document.getElementById("navbarNavDropdown");
      if (navbar && !navbar.classList.contains("show")) {
        navbar.classList.add("collapsing");
        navbar.style.height = "0px";
        setTimeout(() => {
          navbar.classList.remove("collapsing");
          navbar.style.height = "";
        }, 30);
      }
    },
  },
};
</script>

<style scoped>
.smooth-collapse {
  transition: height 0.3s ease;
}

.collapsing {
  height: 0 !important;
}
</style>
