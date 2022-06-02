<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <one-index></one-index>
  <two-index></two-index>
  
</template>

<script>
import TwoIndex from './components/TwoIndex.vue'
import OneIndex from './components/OneIndex.vue'

export default {
  name: 'App',
  components: {
    OneIndex,
    TwoIndex,
  }

}
</script>
