<template>
  <div id="app">
    <main-tab-bar></main-tab-bar>
    <router-view></router-view>
  </div>
</template>

<script>
  import MainTabBar from './components/tabbar/MainTabBar'
export default {
  name: 'App',
  components:{
    MainTabBar
  }
}
</script>
<style>
  @import './assets/css/base.css';
  /* body{
    padding: 0;
    margin: 0;
  } */
</style>
