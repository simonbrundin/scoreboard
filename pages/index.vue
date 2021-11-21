<template>
  <div class="flex flex-col items-center">
    <Nuxt-link to="/input"><button>Poängräknare</button></Nuxt-link
    ><Nuxt-link to="/output"><button>Overlay - in i vMix</button></Nuxt-link
    ><Nuxt-link to="/settings"><button>Inställningar</button></Nuxt-link>
  </div>
</template>

<script setup></script>

<style scoped>
button {
  background: blue;
  color: white;
  padding: 10px;
  margin-bottom: 10px;
}
</style>
