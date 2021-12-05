<template>
  <!-- <el-container>
    <Aside></Aside> -->
  <el-container direction="vertical">
    <Header></Header>
    <el-main>
      <nuxt />
    </el-main>
    <Footer></Footer>
  </el-container>
  <!-- </el-container> -->
</template>

<script>
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import Aside from "@/components/Aside.vue";
export default {
  components: {
    Header,
    Footer,
    Aside,
  },
};
</script>

<style lang="less" scoped>
.el-main {
  padding: 0;
  overflow-y: scroll;
}
</style>