<template>
  <div id="app">
    <PageHeader/>
    <router-view/>
  </div>
</template>

<script>
import PageHeader from '@/components/parts/PageHeader'

export default {
  name: 'App',
  components: { PageHeader }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
