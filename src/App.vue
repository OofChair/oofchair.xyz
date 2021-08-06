<!-- This example requires Tailwind CSS v2.0+ -->
<template>
<link rel="stylesheet" href="https://rsms.me/inter/inter.css">
<div class="bg-black">
  <header class="bg-black">
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
      <div class="w-full py-6 flex items-center justify-between lg:border-none">
        <div class="flex items-center">
          <a href="#">
            <span class="sr-only">OofChair</span>
            <img class="h-14 w-auto" src="https://cdn.discordapp.com/attachments/769165401879478302/872913324545835028/oofcoins.png" alt="" />
          </a>
          <div class="hidden ml-10 space-x-8 lg:block">
            <a v-for="link in navigation" :key="link.name" :href="link.href" class="text-base font-medium text-white hover:text-gray-500 transition ease-in-out duration-500">
              {{ link.name }}
            </a>
          </div>
        </div>
      </div>
      <div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">
        <a v-for="link in navigation" :key="link.name" :href="link.href" class="text-base font-medium text-white hover:text-gray-500">
          {{ link.name }}
        </a>
      </div>
    </nav>
  </header>

  <div id="home">
    <div class="max-w-7xl mx-auto py-16 px-4 sm:py-24 sm:px-6 lg:px-8">
      <div class="text-center">
        <span class="block text-transparent bg-clip-text text-8xl bg-gradient-to-r font-bold from-red-600 to-yellow-300 xl:inline">I'm OofChair</span>
        <p class="max-w-xl mt-5 mx-auto text-xl text-gray-500">I'm a beginner Python developer and an intermediate web developer.</p><br>
        <a href="#about"><button type="button" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-red-800 hover:bg-red-500 transition ease-in-out duration-300" href="#about">What do you do?</button></a>
      </div>
    </div>
    
    
  </div>

  <div class="relative py-16 bg-black overflow-hidden" id="about">
    <div class="hidden lg:block lg:absolute lg:inset-y-0 lg:h-full lg:w-full">
      <div class="relative h-full text-lg max-w-prose mx-auto" aria-hidden="true">
        <svg class="absolute top-12 left-full transform translate-x-32" width="404" height="384" fill="none" viewBox="0 0 404 384">
          <defs>
            <pattern id="74b3fd99-0a6f-4271-bef2-e80eeafdf357" x="0" y="0" width="20" height="20" patternUnits="userSpaceOnUse">
              <rect x="0" y="0" width="4" height="4" class="text-gray-200" fill="currentColor" />
            </pattern>
          </defs>
          <rect width="404" height="384" fill="url(#74b3fd99-0a6f-4271-bef2-e80eeafdf357)" />
        </svg>
      </div>
    </div>
    
    <div class="relative px-4 sm:px-6 lg:px-8" id="portfolio">
      <div class="text-lg max-w-prose mx-auto">
        <h1>
          <span class="mt-2 block text-6xl text-center leading-8 font-extrabold tracking-tight text-gray-200 sm:text-4xl">About me</span>
        </h1>
        <p class="mt-8 text-xl text-white leading-8">I'm a beginner Python dev who writes Discord bots and an intermediate web developer looking for a job.</p>
      </div>
      <div class="mt-6 prose prose-indigo prose-lg text-white mx-auto">
        <p>My current projects are my <a href="https://discord.red"><button class="text-red-800 underline font-bold hover:text-red-500 transition ease-in-out duration-300">Red-DiscordBot</button></a> cogs (found <a href="https://github.com/OofChair/OofCogs"><button class="text-red-800 underline font-bold hover:text-red-500 transition ease-in-out duration-300">here</button></a>) a semi-public Discord bot,  a Python wrapper of <a href="https://some-random-api.ml"><button class="text-red-800 underline font-bold hover:text-red-500 transition ease-in-out duration-300">Some-Random-API</button></a>, and more. You can find my GitHub <a href="https://github.com/OofChair"><button class="text-red-800 underline font-bold hover:text-red-500 transition ease-in-out duration-300">here</button></a></p>
      </div>
    </div>
  </div>

  <div class="relative px-4 sm:px-6 lg:px-8 p-8" id="commissions">
      <div class="text-lg max-w-prose mx-auto">
        <h1>
          <span class="mt-2 block text-6xl text-center leading-8 font-extrabold tracking-tight text-gray-200 sm:text-4xl">Commissions</span>
        </h1>
        <p class="mt-8 text-xl text-white leading-8">I take commissions! You can find my contact information below.</p>
      </div>
      <div class="mt-6 prose prose-indigo prose-lg text-white mx-auto">
        <p>Some things you can commission me for are:</p>
        <ul>
          <li>Customized Discord bots</li>
          <li>Websites</li>
          <li>Speciality (contact me)</li>
        </ul>
        <p>You can contact me with the links above or my contact form below.</p>
      </div>
    </div>
  </div>
  

  <div class="relative px-4 sm:px-6 lg:px-8" id="contact">
      <div class="text-lg max-w-prose mx-auto">
        <h1>
          <span class="mt-2 block text-6xl text-center leading-8 font-extrabold tracking-tight text-gray-200 sm:text-4xl">Contact</span>
        </h1>
        <p class="mt-8 text-xl text-white leading-8">You can contact me through Discord by joining my Discord server <a href="https://discord.gg/3PfU5q22wN"><button class="text-red-800 underline font-bold hover:text-red-500 transition ease-in-out duration-300">here</button></a>, or by emailing me <a href="mailto:oofchairr@gmail.com"><button class="text-red-800 underline font-bold hover:text-red-500 transition ease-in-out duration-300">here</button></a>.</p>
      </div>
      <div class="mt-6 prose prose-indigo prose-lg text-white mx-auto">
        <p class="font-bold">I look forward to working with you!</p>
      </div>
    </div>

  <footer class="bg-black">
    <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8" aria-label="Top">
      <div class="w-full py-6 flex items-center justify-between lg:border-none">
        
        <div class="flex items-center">
          <a href="#home">
            <span class="sr-only">OofChair</span>
            <img class="h-14 pr-64 w-auto" src="https://cdn.discordapp.com/attachments/769165401879478302/872913324545835028/oofcoins.png" alt="" />
          </a>
            <a href="https://github.com/OofChair">
                <span class="sr-only">GitHub</span>
                <img class="h-10 pl-64 object-right w-auto" src="https://cdn.discordapp.com/attachments/769165401879478302/873014766703116314/github.png" alt="" />
            </a>
            <a href="https://discord.gg/3PfU5q22wN">
                <span class="sr-only">Discord</span>
                <img class="h-10 pr-64 pl-8 w-auto" src="https://cdn.discordapp.com/attachments/769165401879478302/873018187397091388/discord.png" alt="" />
            </a>
            <p class="font-bold text-white"><a href="https://github.com/OofChair/oofchair.xyz">©️ OofChair 2021</a></p>
        </div>
      </div>
      <div class="py-4 flex flex-wrap justify-center space-x-6 lg:hidden">
      </div>
    </nav>
  </footer>

</template>

<script>
const navigation = [
  { name: 'Home', href: '#home' },
  { name: 'About', href: '#about' },
  { name: 'Commissions', href: '#commissions' },
  { name: 'Contact', href: '#contact' },
]

export default {
  setup() {
    return {
      navigation,
    }
  },
}
</script>
