<template>
  <div class="headerBox">
    <div class="header">
      <a class="icon"></a>
      <div class="headerNav">
        <a class="item" href="#">领卷中心</a>
        <a class="item" href="#">社区</a>
      </div>
      <div class="headerSearch">
        <input type="">
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'header'
  }
</script>

<style lang="stylus" scoped>
  .headerBox
    width 1180px
    height 102px
    margin 0 auto
    .header
      height 36px
      padding 30px 0 36px
      .icon
        display block
        width 180px
        height 36px
        float left
        margin-right 50px
      .headerNav
        height 36px
        line-height 36px
        width 500px
        float left
        .item
          font-size 18px
          margin-right 50px
          text-align center
          color #666
      .headerSearch
        float right
</style>
