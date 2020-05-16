<template>
  <div class="nav-bar">
    <aside>
      <vuescroll :ops="scrollBarOpts" ref="vuescroll">
        <router-link class="aside-btns" to="/">Home</router-link>
        <div class="aside-line"></div>
        <router-link class="aside-btns" to="/arena/s3">S3</router-link>
        <router-link class="aside-btns" to="/arena/dynamodb"
          >Dynamodb</router-link
        >
        <div class="aside-line"></div>
        <router-link class="aside-btns" to="/about">About</router-link>
      </vuescroll>
    </aside>
  </div>
</template>

<script>
export default {
  name: "NavBar"
};
</script>
<style lang="scss" scoped>
.nav-bar {
  aside {
    position: absolute;
    top: 70px;
    bottom: 0;
    left: 0;
    width: 140px;
    padding: 30px;
    background-color: rgb(33, 37, 43);
    border-right: 1px solid rgb(33, 37, 43);
    .aside-btns {
      display: block;
      width: 100%;
      margin-top: 12px;
      font-size: 12px;
      color: white;
      font-family: Arial;
    }
    .aside-line {
      display: block;
      width: calc(100% + 10px);
      margin: 12px -5px 6px -5px;
      border-bottom: 1px solid rgb(127, 130, 139);
    }
  }
}
</style>
