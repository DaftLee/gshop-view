<template>
  <div id='app'>
    <router-view></router-view>
    <!-- 通过路由中配置的meta属性，自定义是否显示底部 -->
    <FootGuider v-show="$route.meta.showFooter"></FootGuider>
  </div>
</template>

<script>
import FootGuider from './components/FootGuider/FootGuider'
export default {
  components: {
    FootGuider
  }
}
</script>
<style lang="stylus" ref="stylesheet/stylus">
.app
  width 100%
  height 100%
  background #f5f5f5
</style>
