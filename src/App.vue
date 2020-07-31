<template>
  <div id="app">
    <!-- 路由出口 -->
    <router-view />
    <div class="box"></div>
    <h1>黑马头条</h1>
    <i class="toutiao toutiao-dianzan2"></i>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style lang="less">
.box {
  height: 200px;
  width: 375px;
  background-color: hotpink;
}
</style>
