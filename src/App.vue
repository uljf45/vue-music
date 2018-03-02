<template>
  <div id="app">
    <!-- <h1>hello world</h1>
    <Test></Test> -->
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>

</template>

<script>
import Test from 'components/Test.vue'
import MHeader from 'components/m-header/m-header'
import Tab from 'components/tab/tab'
export default {
  name: 'App',
  components: {
    Test,
    MHeader,
    Tab
  }
}
</script>

<style lang="stylus">
  @import "~common/stylus/variable.styl"
  #app
    $color-text
</style>
