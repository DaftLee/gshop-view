<template>
  <div class="order">
    <header class="header">
      <a class="header_title">
        <span class="header_title_text">订单列表</span>
      </a>
    </header>
    <div class="order_no_login">
      <img src="./images/order/person.png">
      <h3>登录后查看外卖订单</h3>
      <button>立即登录</button>
    </div>
  </div>
</template>
<script>
export default {

}
</script>

<style lang="stylus" ref="stylesheet/stylus">
@import '../../common/stylus/mixins.styl'
.order // 订单
  width 100%
  .header
    background-color #67ABD6
    position fixed
    z-index 100
    left 0
    top 0
    width 100%
    height 45px
    .header_title
      position absolute
      top 50%
      left 50%
      transform translate(-50%, -50%)
      width 50%
      color #fff
      text-align center
      .header_title_text
        font-size 20px
        color #fff
        display block
  .order_no_login
    padding-top 140px
    width 60%
    margin 0 auto
    text-align center
    >img
      display block
      width 100%
      height 30%
    >h3
      padding 10px 0
      font-size 17px
      color #6a6a6a
    >button
      display inline-block
      background #67ABD6
      font-size 14px
      color #fff
      border 0
      outline none
      border-radius 5px
      padding 10px 20px
</style>
