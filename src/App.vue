<template>
  <div id="app">
    <MHeader></MHeader>
    <tab></tab>
    <router-view></router-view>
  </div>
</template>

<script>
  import MHeader from './components/m-header/m-header'
  import Tab from './components/tab/tab'
  export default {
    components: {
        MHeader,
        Tab
    }
  }
</script>


<style lang="stylus" rel="stylesheet/stylus">
  @import "./common/stylus/variable";
  
  #app 
    color: $color-theme
</style>

