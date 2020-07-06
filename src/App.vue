<template>
  <div>
    <header-vue></header-vue>
    <game-vue></game-vue>
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Game from './components/Game.vue'

export default {
  name: 'Minesweeper',
  components: {
    'header-vue': Header,
    'game-vue': Game
  },
  data() {
    return {
      
    }
  }
}
</script>

<style>

</style>
