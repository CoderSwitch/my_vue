<template>
<div class="header">
  <div class="header-left"><span class="iconfont">&#xe743;</span></div>
  <div class="header-input"><span class="iconfont">&#xe7b3;</span>输入城市/景点/游玩主题</div>
  <div class="header-right">城市<span class="iconfont arrow-icon">&#xe64a;</span></div>
</div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
  @import "../../assets/styles/varibles.style"
  .header
    margin-top:0
    display:flex
    line-height :.86rem
    background :$bgColor
    color:#ffffff
    .header-left
      padding-left :.2rem
      width:.64rem
      float:left
    .header-input
      flex:1
      background :#ffffff
      border-radius:.1rem
      margin-top :.12rem
      margin-left :.2rem
      color :#ccc
      line-height :.64rem
      height :.64rem
      padding-left :.2rem
    .header-right
      width:1.24rem
      float: right
      text-align:center
      .arrow-icon
        font-size:.24rem
</style>
