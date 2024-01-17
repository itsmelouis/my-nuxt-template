<template>
  <div
    class="fixed flex flex-row justify-between items-center gap-5 px-4 py-2 mt-4 md:mt-6 rounded-md bg-white/60 dark:bg-[#121212]/60 border border-gray-900 backdrop-blur-lg w-10/12 md:w-2/5 z-50"
  >
    <div class="flex flex-row items-center justify-between gap-2">
      <ColorSchemeToggle />
      <NuxtLink
        class="hover:bg-gray-700/5 dark:hover:bg-[#c8c8dc]/5 dark:text-white cursor-pointer px-4 py-2 text-sm rounded-md text-black/80 hover:text-black dark:text-white/80 dark:hover:text-white transition-all duration-75"
        to="/"
      >
        Home
      </NuxtLink>
    </div>

    <div class="flex flex-row items-center justify-between gap-2">
      <a
        target="_blank"
        href="https://github.com/itsmelouis"
        rel="noreferrer"
        class="p-2 rounded-md bg-transparent hover:bg-black/5 dark:hover:bg-white/5 cursor-pointer"
      > <div class="i-ph-github-logo w-6 h-6" /> </a>
    </div>
  </div>
</template>
