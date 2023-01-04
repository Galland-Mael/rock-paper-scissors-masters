<template>
  <div class="game-container flex">
    <div class="traingle-container flex ">
      <img src="../images/bg-triangle.svg" alt="triangle" class="triangle">
      <div class="shape paper flex blue-border">
        <img src="../images/icon-paper.svg" alt="paper" class="img rotate">
      </div>
      <div class="shape rock flex red-border">
        <img src="../images/icon-rock.svg" alt="rock" class="img rotate">
      </div>
      <div class="shape scissors flex yellow-border">
        <img src="../images/icon-scissors.svg" alt="scissors" class="img">
      </div>
    </div>
  </div>
  <div class="rules flex">
    <p class="rules-text">RULES</p>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Board'
}
</script>

<style scoped>
@import "/src/CSS/board.css";
</style>
