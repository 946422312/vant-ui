<template>
  <div id="app">
    <van-nav-bar title="长沙黑马" left-text="返回" left-arrow @click-right="onClickRight"/>

    <van-tabbar v-model="active" active-color="pink">
      <van-tabbar-item icon="home-o">标签</van-tabbar-item>
      <van-tabbar-item icon="search" dot>标签</van-tabbar-item>
      <van-tabbar-item icon="friends-o" info="5">标签</van-tabbar-item>
      <van-tabbar-item icon="setting-o" info="20">标签</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: "App",
  
  methods: {
    onClickRight() {}
  },
  data() {
    return {
      active: 0
    }
  }
};
</script>

<style>
#app {
}
</style>
