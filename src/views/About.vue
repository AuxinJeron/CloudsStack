<template>
  <div class="about">
    <header>
      <nav-menu></nav-menu>
    </header>
    <nav-bar></nav-bar>
    <section>
      <h4>About</h4>
    </section>
  </div>
</template>

<script>
import NavMenu from "@/components/NavMenu.vue";
import NavBar from "@/components/NavBar.vue";
export default {
  name: "About",
  components: { NavMenu, NavBar }
};
</script>

<style lang="scss" scoped>
.about {
  height: 100%;
  width: 100%;
  min-width: 500px;
  position: relative;
  header {
    width: 100%;
    height: 70px;
  }
  section {
    position: absolute;
    top: 70px;
    bottom: 0;
    left: 200px;
    right: 0;
    padding: 20px 25px;
  }
}
</style>
