<template>
  <div class="header">
    <div class="head-left">返回</div>
    <div class="head-input">输入景点/城市/游玩主题</div>
    <div class="head-right">城市</div>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
.header
  line-height: .86rem
  display: flex
  background: #25a4bb
  color: #fff;
  .head-left
    text-align: center;
    float: left
    width: .64rem
  .head-input
    margin-top: .12rem
    margin-left: .2rem
    flex: 1
    height: .64rem
    padding 0 .1rem
    line-height: .64rem
    background: #fff;
    border-radius: .1rem
    color #ccc
  .head-right
    width: 1.24rem
    float: right
    text-align: center
</style>
