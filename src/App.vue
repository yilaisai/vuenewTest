<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view/>
    </keep-alive>
    <player></player>
  </div>
</template>

<script>
  import Tab from 'components/tab/tab'
  import MHeader from 'components/m-header/m-header'
  import Player from 'components/player/player'

  export default {
    components: {
      Tab,
      MHeader,
      Player
    }
  }
</script>

<style scoped lang="stylus">

</style>
