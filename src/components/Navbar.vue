<template>
  <div>
    <b-navbar
      id="navigation"
      toggleable="lg"
      variant="faded"
      class="navbar-dark"
      fixed="top"
      v-on:scroll="handleScroll"
    >
      <b-navbar-brand href="#">
        <img src="../assets/output-onlinepngtools.png" alt="hello" width="80" height="50" />
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto" id="right-nav">
          <b-nav-item href="#about">About</b-nav-item>
          <b-nav-item href="#project-site">Project</b-nav-item>
          <b-nav-item href="#contact">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  methods: {
    handleScroll(event) {
      const element = document.getElementById("navigation");
      if (window.scrollY > 50) {
        element.classList.add("navbar-custom");
      } else if (window.scrollY < 530) {
        element.classList.remove("navbar-custom");
      }
    }
  },
  created() {
    window.addEventListener("scroll", this.handleScroll);
  },
  destroyed() {
    window.removeEventListener("scroll", this.handleScroll);
  }
};
</script>

<style>
#navigation {
  transition: 0.2s ease-in-out;
}
.navbar-custom {
  background-color: #202026;
}
.navbar-brand {
  margin-left: 5%;
}

#right-nav {
  margin-right: 17%;
}

#right-nav .nav-item {
  margin-right: 30%;
}
</style>
