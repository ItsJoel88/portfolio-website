<template>
  <div id="app">
    <Navbar />
    <Hello />
    <div id="footer">
      <Contact />
    </div>
  </div>
</template>

<script>
import Navbar from "./components/Navbar";
import Contact from "./components/Contact";
import Hello from "./components/Hello";

export default {
  components: {
    Navbar,
    Contact,
    Hello
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
