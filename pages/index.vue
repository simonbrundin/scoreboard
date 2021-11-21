<template>
  <div class="flex flex-col items-center">
    <NuxtLink to="/input"><button>Poängräknare</button></NuxtLink
    ><NuxtLink to="/output"><button>Overlay - in i vMix</button></NuxtLink
    ><NuxtLink to="/settings"><button>Inställningar</button></NuxtLink>
  </div>
</template>

<script setup></script>

<style scoped>
button {
  background: blue;
  color: white;
  padding: 10px;
  margin-bottom: 10px;
  font-size: 20px;
}
</style>
