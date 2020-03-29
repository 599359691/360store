<template>
  <div class="topBar">
    <div class="main">
      <div class="topBar-left">
        <a class="item-left" href="#">帮助中心</a>
        <a class="item-left" href="#">收藏</a>
        <a class="item-left" href="#">360官网</a>
      </div>
      <div class="topBar-right">
        <a class="item-right" href="#">登录</a>
        <a class="item-right" href="#">注册</a>
        <a class="item-right" href="#">手机商城</a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'topBar'
  }
</script>

<style scoped lang="stylus">
  .topBar
    width 100%
    height 40px
    background-color #333

    .main
      width 1180px
      height 40px
      margin 0 auto

      .topBar-left
        float left

        .item-left
          display inline-block
          font-size 12px
          text-align center
          margin-right 25px
          line-height 40px
          color #fff

      .topBar-right
        float right

        .item-right
           display inline-block
           font-size 12px
           text-align center
           margin-left 25px
           line-height 40px
           color #fff
</style>
