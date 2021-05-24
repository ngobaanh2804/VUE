<template>
  <div id="app">
    <TheHeader/>
    <TheContent/>
    <TheFooter/>
  </div>
</template>

<script>
import TheHeader from './components/layout/TheHeader.vue'
import TheContent from './components/layout/TheContent.vue'
import TheFooter from './components/layout/TheFooter.vue'


export default {
  name: 'App',
  components: {
    TheHeader,
    TheContent,
    TheFooter

  }
}
</script>

<style>

@import "./css/components/input.css";
@import "./css/components/button.css";
@import "./css/page/mapScrapy.css";
@import "./css/common.css";
</style>
