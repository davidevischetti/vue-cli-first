<template>
  <div id="app">
    <NewTitle/>
    <JumboTron/>
  </div>
</template>

<script>
import NewTitle from './components/NewTitle.vue'
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    NewTitle,
    JumboTron
}
}
</script>

<style lang="scss">
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
</style>
