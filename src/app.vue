<template>
    <div id="app">
        <tab></tab>
        <router-view></router-view>
        <b-nav></b-nav>
    </div>
</template>

<script>
  import Tab from 'component/tab/tab'
  import BNav from 'component/b-nav/b-nav'

  export default {
    components: {
      Tab,
      BNav
    }
  }
</script>

<style scoped>

</style>