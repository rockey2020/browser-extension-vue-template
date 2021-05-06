<template>
  <div
    class="App da-flex-reset-css da-flex-reset-css-all da-flex-reset-css-all-child"
  >
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
  created() {
    let b, z;
    let a = [1, { name: 1 }];

    let test = function () {
      return a;
    };
    let namespaceA = 1;
    console.log(a);
  },
};
</script>
<style lang="less">
@import "~darwin-flex-layout";
@import "./assets/styles/common";
</style>
