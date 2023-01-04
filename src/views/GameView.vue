<template>
  <div class="container">
    <scoreboard/>
    <board/>
  </div>
</template>

<script>
// @ is an alias to /src
import Scoreboard from '@/components/Scoreboard'
import Board from '@/components/Board'

export default {
  name: 'GameView',
  components: {
    Board,
    Scoreboard
  }
}
</script>

<style scoped>
@import "/src/CSS/game.css";
@import "/src/CSS/all.css";
</style>
