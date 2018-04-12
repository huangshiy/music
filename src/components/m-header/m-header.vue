<template>
  <div class="m-header">
    <div class="icon"></div>
    <h1 class="text">Chicken Music</h1>
  </div>
</template>

<script>

export default {
//   name: 'm-header',
  // data () {
  //   return {
  //     msg: 'Welcome to Your Vue.js App'
  //   }
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "../../common/stylus/variable"
  @import "../../common/stylus/mixin"
//    @import "common/stylus/variable"
//    @import "common/stylus/mixin"
  .m-header
    position: absolute
    transform :translate(0,0)
    width:100%
    background-color :gray
    margin :0 auto
    height: 44px
    
    top:0px
    text-align: center
    color: $color-theme
    font-size: 0
    .icon
      display: inline-block
      vertical-align: top
      margin-top: 6px
      width: 30px
      height: 32px
      margin-right: 9px
      bg-image('logo')
      background-size: 30px 32px
    .text
      display: inline-block
      vertical-align: top
      text-align :center
      line-height: 44px
      font-size: $font-size-large
    // .mine
    //   position: absolute
    //   top: 0
    //   right: 0
    //   .icon-mine
    //     display: block
    //     padding: 12px
    //     font-size: 20px
    //     color: $color-theme
</style>
