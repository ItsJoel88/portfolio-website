<template>
  <div id="app">
    <Navbar />
    <About />
    <Project />
    <div id="footer">
      <Contact />
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import About from "./components/About";
import Contact from "./components/Contact";
import Project from "./components/Project";

export default {
  components: {
    Navbar,
    About,
    Contact,
    Project
  }
};
</script>

<style>
#footer {
  position: relative;
  text-align: center;
  bottom: 0;
  width: 100%;
}
</style>
