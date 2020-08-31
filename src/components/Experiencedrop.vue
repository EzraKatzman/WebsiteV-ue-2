<template>
    <div class="mx-2">
        <button @click="isOpen = !isOpen" class="block mt-2 rounded-md bg-teal-300 border border-teal-400 w-full focus:outline-none focus:shadow-outline">
            <p class="text-teal-600 hover:text-white">Experience</p>
        </button>
        <div v-if="isOpen" class="my-2 p-2 bg-gray-100 rounded-lg shadow-lg border border-teal-400">
            <div class="m-2 p-2">
                <h2 class="font-semibold text-xl text-gray-800 ml-2">Place of work: </h2>
                <p class="mx-2 text-gray-600 uppercase font-semibold tracking-wide text-xs">Start date - end date</p>
                <p class="m-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores consequuntur, ad beatae provident ea fugit! Corrupti 
                    quas tenetur explicabo sunt in rerum sed officia possimus qui! Quo eum aut dignissimos? Lorem, ipsum dolor sit amet consectetur 
                    adipisicing elit. Cum assumenda dignissimos quasi voluptatem necessitatibus qui eaque perferendis magnam, beatae, saepe autem error rem, 
                    possimus asperiores vel. Cupiditate nisi quos ea.</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            isOpen: false
        }
    }
}
</script>