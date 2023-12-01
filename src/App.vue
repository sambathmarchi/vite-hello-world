<script>
import HelloWorld from './components/HelloWorld.vue'
import Jumbo from './components/Jumbo.vue'
import MainContent from './components/MainContent.vue'

export default {
  components: {
    HelloWorld,
    Jumbo,
    MainContent
  }
}
</script>

<template>
  <Jumbo />
  <HelloWorld />
  <MainContent />
</template>

<style scoped>
template {
  overflow: auto;
}
</style>
