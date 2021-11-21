<template>
  <div class="players pl-4 pr-4 px-4 w-240px">
    <div class="player1 flex items-center justify-between">
      <div class="name pr-2">{{ player1 }}</div>
      <img src="@/assets/flags/se.png" />
    </div>
    <div class="player2 flex items-center justify-between">
      <div class="name pr-2">{{ player2 }}</div>
      <img src="@/assets/flags/no.png" />
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  player1: String,
  player2: String,
});
</script>

<style scoped>
.name {
  text-transform: uppercase;
}
img {
  height: 20px;
}
</style>
