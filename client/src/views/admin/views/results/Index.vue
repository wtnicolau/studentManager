<template>
  <transition name="el-zoom-in-center"
    mode="out-in">
    <router-view></router-view>
  </transition>

</template>

<script>
export default {
  mounted() {},
  data() {
    return {};
  },
  created() {}
};
</script>

<style lang='stylus' scoped></style>