<template>
  <div id="app">
   <router-view></router-view>
   <van-tabbar v-model="active">
  <van-tabbar-item icon="home-o">首页</van-tabbar-item>
  <van-tabbar-item icon="search" dot>查询</van-tabbar-item>
  <van-tabbar-item icon="friends-o" >联系人</van-tabbar-item>
  <van-tabbar-item icon="setting-o" info="20">设置</van-tabbar-item>
</van-tabbar>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      active: 0
    }
  },
}
</script>

<style>
#app {
 
}
</style>
