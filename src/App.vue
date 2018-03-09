<template>
  <div id="app">
    <!-- <h1>hello world</h1>
    <Test></Test> -->
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <player></player>
  </div>

</template>

<script>
import Test from 'components/Test.vue'
import MHeader from 'components/m-header/m-header'
import Tab from 'components/tab/tab'
import Player from 'components/player/player'

export default {
  name: 'App',
  components: {
    Test,
    MHeader,
    Tab,
    Player
  }
}
</script>

<style lang="stylus">
  @import "~common/stylus/variable.styl"
  #app
    $color-text
</style>
