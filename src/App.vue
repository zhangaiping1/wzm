<template>
  <div id="app">
    <router-view/>
    <h1>移动端</h1>
    <div>
      <i class="iconfont icon-RectangleCopy11"></i>
    </div>

    <div>-----------------------------------------</div>
    <van-swipe class="my-swipe" :autoplay="3000" indicator-color="white">
      <van-swipe-item>1</van-swipe-item>
      <van-swipe-item>2</van-swipe-item>
      <van-swipe-item>3</van-swipe-item>
      <van-swipe-item>4</van-swipe-item>
    </van-swipe>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
  .my-swipe .van-swipe-item {
    color: #fff;
    font-size: 20px;
    line-height: 150px;
    text-align: center;
    background-color: #39a9ed;
  }
</style>
