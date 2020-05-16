<template>
  <div class="nav-menu">
    <div class="nav-logo">
      <span class="nav-logo-text">{{ logoText }}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavMenu",
  data() {
    return {
      logoText: "Cloud Stack"
    };
  }
};
</script>

<style lang="scss" scoped>
.nav-menu {
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  padding: 20px;
  color: #ffffff;
  transition: all 0.4s ease;
  user-select: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  -webkit-user-drag: none;
  background-color: rgb(40, 44, 52);
  box-shadow: 1px 1px 4px 1px rgba(40, 44, 52, 0.7);
}
.nav-logo-text {
  margin-left: 14px;
  padding-top: 10px;
  font-size: 20px;
  color: #ffffff;
  font-weight: 600;
}
</style>
