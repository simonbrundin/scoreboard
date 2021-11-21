<template>
  <div>
    <div class="team">
      <Team :player1="'Emma Wallin'" :player2="'Lotta Nyman'" />
      <div class="sets flex">
        <div class="set1">1</div>
        <div class="set2">2</div>
        <div class="set3">3</div>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.team {
  border: 1px solid black;
}
.sets div {
  border: 1px solid black;
  padding: 10px;
}
.team {
  display: flex;
  align-items: center;
}
.players div {
  display: flex;
}
.name {
  margin-right: 10px;
}
.players img {
  height: 20px;
}
</style>
