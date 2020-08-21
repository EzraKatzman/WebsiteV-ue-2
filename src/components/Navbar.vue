<template>
    <header class="bg-gradient-to-l from-orange-300 to-orange-400 sm:flex sm:justify-between sm:items-center sm:px-4 sm:py-3 border-b-2 border-orange-300">
    <div class="flex items-center justify-between px-4 py-3 sm:p-0">
      <div class="text-white">
        <h2 class="font-semibold">Azriel Katzman</h2>
      </div>
      <div class="sm:hidden">
        <button @click="isOpen = !isOpen" type="button" class="block text-orange-700 hover:text-white focus:text-white focus:outline-none">
          <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
            <path v-if="isOpen" fill-rule="evenodd" d="M18.278 16.864a1 1 0 0 1-1.414 1.414l-4.829-4.828-4.828 4.828a1 1 0 0 1-1.414-1.414l4.828-4.829-4.828-4.828a1 1 0 0 1 1.414-1.414l4.829 4.828 4.828-4.828a1 1 0 1 1 1.414 1.414l-4.828 4.829 4.828 4.828z"/>
            <path v-if="!isOpen" fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"/>
          </svg>
        </button>
      </div>
    </div>
    <nav :class="isOpen ? 'block' : 'hidden'" class="px-2 pt-2 pb-4 md:flex sm:p-0">
      <a href="#" class="block px-2 py-1 text-orange-700 font-semibold  hover:text-white focus:text-white">Experience</a>
      <a href="#" class="mt-1 block px-2 py-1 text-orange-700 font-semibold sm:mt-0 sm:ml-2 hover:text-white focus:text-white">Projects</a>
      <a href="#" class="mt-1 block px-2 py-1 text-orange-700 font-semibold sm:mt-0 sm:ml-2 hover:text-white focus:text-white">Contact</a>
    </nav>
  </header>
</template>

<script>
export default {
    data() {
        return {
            isOpen: false,
        }
    }
}
</script>