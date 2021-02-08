<template>
  <div class="flex flex-col h-screen bg-black bg-opacity-75 font-mono" id="app">
    <div class="m-auto text-white">
      <h1 class="text-center py-5">🇨🇴 Manuel Cañarte 🇨🇦</h1>
      <div class="flex justify-between">
        <a href="https://blog.manuelcanarte.com/" target="_blank" class="underline hover:bg-red-500 px-3">Blog</a>
        <a href="https://github.com/macv93" target="_blank" class="underline hover:bg-red-500 px-3">Github</a>
        <a href="https://www.instagram.com/spuddy_raspaspa/" target="_blank" class="underline hover:bg-red-500 px-3">Instagram</a>
        <a href="https://www.linkedin.com/in/manuel-canarte/" target="_blank" class="underline hover:bg-red-500 px-3">Linkedin</a>
      </div>
      <img class="m-auto rounded-tl-full rounded-tr-full py-5" src="./assets/manny.png" alt="A picture of Manuel">
      <p class="text-center">Hola! I'm Manuel, a software dev on the path to mastery.</p>
    </div>
    <footer class="py-2 text-center text-white">️Cañarte © {{ new Date().getFullYear() }}</footer>
  </div>
</template>

<script>

export default {
  name: 'App',
  methods: {
    reverseString(str) {
      return str.split("").reverse().join("");
    }
  }
}
</script>

