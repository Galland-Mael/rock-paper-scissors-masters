<template>
  <div class="scoreboard flex">
    <div class="text-container">
      <div class="split">
        <span class="text">Rock</span>
      </div>
      <div class="split">
        <span class="text">PAPER</span>
      </div>
      <div class="split">
        <span class="text">SCISSORS</span>
      </div>
    </div>
    <div class="full-width score-container">
      <div class="score flex column">
        <span class="full-width title-score">Score</span>
        <span class="score-text">12</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Scoreboard'
}
</script>

<style scoped>
@import "/src/CSS/scoreboard.css";
@import "/src/CSS/all.css";
</style>
