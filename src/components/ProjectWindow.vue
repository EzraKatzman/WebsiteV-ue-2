<template>
    <div class="m-2 p-2 bg-gray-100 rounded-lg shadow-lg border border-orange-400">
        <h2 class="p-2 m-2 text-xl text-gray-800 font-bold text-center">Personal Projects</h2>
        <div class="m-2 p-2">
            <h2 class="font-semibold text-xl text-gray-800 ml-2">Truth Table Generator: </h2>
            <p class="mx-2">
                <span class="badge lg:mr-1 bg-orange-500">HTML</span>
                <span class="badge lg:mr-1 bg-blue-500">CSS</span>
                <span class="badge lg:mr-1 bg-yellow-500">Javascript</span>
                <span class="badge lg:mr-1 bg-purple-600">Bootstrap</span></p>
            <p class="m-2">A project made for easily graphing truth tables in propositional logic. Users can insert their logical statements
                (with proper formatting enforced by the system), and see the resulting table with the click of a button.</p>
            <a href="https://github.com/EzraKatzman/Truth-Table-Generator" target="_blank" class="btn inline-block">View Code</a><a href="https://ezrakatzman.github.io/Truth-Table-Generator/" target="_blank" class="btn inline-block">View Site</a>
        </div>
        <hr class="m-2">
        <div class="m-2 p-2">
            <h2 class="font-semibold text-xl text-gray-800 ml-2">"Jackbot" Discord Bot: </h2>
            <p class="mx-2 align-baseline">
                <span class="badge lg:mr-1 bg-blue-600">Python</span>
                <span class="badge lg:mr-1 bg-indigo-600">Discord API</span>
                <span class="badge lg:mr-1 bg-blue-400">Sqlite</span>
                <span class="text-gray-600 uppercase font-semibold tracking-wide text-xs">(Work in progress)</span> </p>
            <p class="m-2"> Jackbot is a bot for the discord app, with the goal of emulating casino games such as crash, slots, blackjack, 
                dice games, and more. It also has a working level system, multiplayer interaction, and a functioning economy.</p>
            <a href="" target="_blank" class="btn inline-block">View Code</a>
        </div>
        <hr class="m-2">
        <div class="m-2 p-2">
            <h2 class="font-semibold text-xl text-gray-800 ml-2">Idea Vault: </h2>
            <p class="mx-2 align-baseline">
                <span class="badge lg:mr-1 bg-blue-600">Python</span>
                <span class="badge lg:mr-1 bg-green-500">Shell</span>
                <span class="badge lg:mr-1 bg-gray-600">Selenium</span></p>
            <p class="m-2">The Idea Vault is a script I can run from my phone (via SSH into a raspberry pi) where I can insert project ideas 
                directly in to my project scrum board on Notion, and make a Github repository for it all with only a few arguments.
            </p>
            <a href="https://github.com/EzraKatzman/Idea-Vault" target="_blank" class="btn inline-block">View Code</a>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script> 