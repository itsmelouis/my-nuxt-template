<script lang="ts" setup>
const colorMode = useColorMode()

function toggleMode() {
  colorMode.preference = colorMode.value === 'light' ? 'dark' : 'light'
}
</script>

<template>
  <button
    class="rounded-lg p-2 hover:bg-active hover:bg-black/5 dark:hover:bg-white/5 cursor-pointer"
    @click="toggleMode"
  >
    <div class="i-ph-sun-dim-duotone dark:i-ph-moon-stars-duotone text-2xl " />
  </button>
</template>
