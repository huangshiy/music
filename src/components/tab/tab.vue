<template>
    <div class="tab">
        <router-link tag="div" to="/recommend" class="tab-item">
            <span class="tab-link">推荐</span>
        </router-link>
        <router-link tag="div" to="/singer" class="tab-item">
            <span class="tab-link">歌手</span>
            </router-link> 
        <router-link tag="div" to="/rank" class="tab-item">
            <span class="tab-link" >排行</span>
        </router-link>
        <router-link tag="div" to="/search" class="tab-item">
            <span class="tab-link">搜索</span>
        </router-link>
    </div>
</template>
<script scoped lang="stylus" rel="stylesheet/stylus">

    export default {
}
</script>
<style scoped lang="stylus" rel="stylesheet/stylus">
@import "../../common/stylus/variable"
/*tag是指定让他跳转的时候跳转到那一类标签*/
  .tab
    display: flex
    height: 44px
    line-height: 44px
    margin-top -16px
    font-size: $font-size-medium
    .tab-item
      flex: 1
      text-align: center
      .tab-link
        padding-bottom: 5px
        color: $color-text-l
      &.router-link-active
        .tab-link
          color: $color-theme
          border-bottom: 2px solid $color-theme

</style>
