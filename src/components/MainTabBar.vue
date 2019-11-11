<template>
  <tab-bar>
      <tab-bar-item path="/home">
        <div class="iconfont" slot="item-icon">&#xe6b8;</div>
        <div class="iconfont" slot="item-icon-active">&#xe6bb;</div>
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <div class="iconfont" slot="item-icon">&#xe706;</div>
        <div class="iconfont" slot="item-icon-active">&#xe7ab;</div>
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <div class="iconfont" slot="item-icon">&#xe6af;</div>
        <div class="iconfont" slot="item-icon-active">&#xe6b9;</div>
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <div class="iconfont" slot="item-icon">&#xe6b7;</div>
        <div class="iconfont" slot="item-icon-active">&#xe735;</div>
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>

<script>
  import TabBar from './tabbar/TabBar'
  import TabBarItem from './tabbar/TabBarItem'
export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style scoped>

</style>
