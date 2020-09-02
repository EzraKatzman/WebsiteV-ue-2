<template>
    <div class="mx-2">
        <button @click="isOpen = !isOpen" class="block mt-2 rounded-md bg-teal-300 border border-teal-400 w-full focus:outline-none focus:shadow-outline">
            <p class="text-teal-600 hover:text-white">Experience</p>
        </button>
        <div v-if="isOpen" class="my-2 p-2 bg-gray-100 rounded-lg shadow-lg border border-teal-400">
            <div class="m-2 p-2">
                <h2 class="font-semibold text-xl text-gray-800 ml-2">Rethink Solutions Inc. </h2>
                <p class="mx-2 text-gray-600 uppercase font-semibold tracking-wide text-xs"> <span class="text-teal-400">Software Developer </span>&middot; May 2020 - September 2020</p>
                <p class="m-2">
                    <ul class="list-disc list-inside m-2">
                        <li>Converted modules to a more modern UI using Apache Wicket</li>
                        <li>Participated in daily standup meetings</li>
                        <li>Collaborated with other team members</li>
                    </ul>
                </p>
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