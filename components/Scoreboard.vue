<template>
  <div>
    <div class="team">
      <div class="players">
        <div class="player1">
          <img src="@/assets/flags/sweden.png" alt="" v-if="false" />
          <div class="name">Simon</div>
        </div>
        <div class="player2">
          <img src="@/assets/flags/sweden.png" alt="" v-if="false" />
          <div class="name">Michael</div>
        </div>
      </div>
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
</style>
