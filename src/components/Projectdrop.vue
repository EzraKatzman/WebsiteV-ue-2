<template>
    <div class="mx-2 mb-2">
        <button @click="isOpen = !isOpen" class="block mt-2 rounded-md bg-teal-300 border border-teal-400 w-full focus:outline-none focus:shadow-outline">
            <p class="text-teal-600 hover:text-white">Projects</p>
        </button>
        <div v-if="isOpen" class="my-2 p-2 bg-gray-100 rounded-lg shadow-lg border border-teal-400 sm:grid-cols-2">
            <div class="m-2 p-2">
                <h2 class="font-semibold text-xl text-gray-800 ml-2">Truth Table Generator: </h2>
                <p class="mx-2">
                    <span class="badge mr-1 bg-orange-500">HTML</span>
                    <span class="badge mr-1 bg-blue-500">CSS</span>
                    <span class="badge mr-1 bg-yellow-500">Javascript</span>
                    <span class="badge mr-1 bg-purple-600">Bootstrap</span></p>
                <p class="m-2">A project made for easily graphing truth tables in propositional logic. Users can insert their logical statements
                    (with proper formatting enforced by the system), and see the resulting table with the click of a button.</p>
                <a href="https://github.com/EzraKatzman/Truth-Table-Generator" target="_blank" class="btn p-2 m-2 inline-block">View Code</a><a href="https://ezrakatzman.github.io/Truth-Table-Generator/" target="_blank" class="btn p-2 m-2 inline-block">View Site</a>
            </div>
            <hr class="m-2">
            <div class="m-2 p-2">
                <h2 class="font-semibold text-xl text-gray-800 ml-2">"Jackbot" Discord Bot: </h2>
                <p class="mx-2 align-baseline">
                    <span class="badge mr-1 bg-blue-600">Python</span>
                    <span class="badge mr-1 bg-indigo-600">Discord API</span>
                    <span class="badge mr-1 bg-blue-400">Sqlite</span>
                    <span class="text-gray-600 uppercase font-semibold tracking-wide text-xs block sm:inline">(Work in progress)</span> </p>
                <p class="m-2"> Jackbot is a bot for the discord app, with the goal of emulating casino games such as crash, slots, blackjack, 
                    dice games, and more. It also has a working level system, multiplayer interaction, and a functioning economy.</p>
                <a href="https://github.com/EzraKatzman/Jackbot" target="_blank" class="btn p-2 m-2 inline-block">View Code</a>
            </div>
            <hr class="m-2">
            <div class="m-2 p-2">
                <h2 class="font-semibold text-xl text-gray-800 ml-2">Idea Vault: </h2>
                <p class="mx-2 align-baseline">
                    <span class="badge mr-1 bg-blue-600">Python</span>
                    <span class="badge mr-1 bg-green-500">Shell</span>
                    <span class="badge mr-1 bg-gray-600">Selenium</span></p>
                <p class="m-2">The Idea Vault is a script I can run from my phone (via SSH into a raspberry pi) where I can insert project ideas 
                    directly in to my project scrum board on Notion, and make a Github repository for it all with only a few arguments.
                </p>
                <a href="https://github.com/EzraKatzman/Idea-Vault" target="_blank" class="btn p-2 m-2 inline-block">View Code</a>
            </div>
            <hr class="m-2">
            <div class="m-2 p-2">
                <h2 class="font-semibold text-xl text-gray-800 ml-2">Enigma Machine: </h2>
                <p class="mx-2 align-baseline">
                    <span class="badge mr-1 bg-yellow-800">Java</span>
                    <span class="text-gray-600 uppercase font-semibold tracking-wide text-xs block sm:inline">(Early Stages)</span></p>
                <p class="m-2">A modern recreation of the Enigma Machine, one of the most famous encryption devices to date. Users can encrypt and decrypt messages, 
                    share them with friends, and get a greater understanding of how the ciphers work. 
                </p>
                <a href="" target="_blank" class="btn p-2 m-2 inline-block">View Code</a>
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