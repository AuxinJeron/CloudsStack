<template>
  <div class="home">
    <header>
      <nav-menu></nav-menu>
    </header>
    <nav-bar></nav-bar>
    <section>
      <h4>Home Page</h4>
    </section>
    <vue-msg :timeout="2000" :top="100" :right="20" ref="vueMsg"></vue-msg>
  </div>
</template>

<script>
import NavMenu from "@/components/NavMenu.vue";
import NavBar from "@/components/NavBar.vue";
import VueMsg from "vue-msgs";
export default {
  name: "Home",
  components: { NavMenu, NavBar, VueMsg }
};
</script>

<style lang="scss" scoped>
.home {
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
