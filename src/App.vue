<template>
  <div id="app">
    <keep-alive>
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>

  export default {
    name: 'App'
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  @import "~assets/css/variable.styl"

  html, body {
    overflow hidden
    overflow-y auto
    width 100%
    height 100%
    padding 0
    margin 0
  }
</style>
