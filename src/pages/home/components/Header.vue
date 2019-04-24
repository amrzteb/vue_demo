<template>
  <div class="header">
    <div class="head-left">返回</div>
    <div class="head-input">内容</div>
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
    background: #fff;
    border-radius: .1rem
  .head-right
    width: 1.24rem
    float: right
    text-align: center
</style>
