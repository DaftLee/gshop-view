<template>
  <div>
    <router-view></router-view>
    <FootGuider></FootGuider>
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
<style lang="stylus" ref="stylesheet/stylus"></style>
