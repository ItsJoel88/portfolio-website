<template>
  <div>
    <b-navbar toggleable="lg" type="light" class="bg-transparent" fixed="top">
      <b-navbar-brand href="#">ItsJoel</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto" id="right-nav">
          <b-nav-item href="#">About</b-nav-item>
          <b-nav-item href="#">Project</b-nav-item>
          <b-nav-item href="#">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style>
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
