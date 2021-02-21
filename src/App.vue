<template>
  <div class="flex flex-col h-screen bg-black bg-opacity-75 font-mono" id="app">
    <div class="m-auto text-white">
      <div class="flex items-center justify-center my-3">
        <div class="font-bold text-center text-lg text-red-600 bg-white rounded-full border-8 border-red-600 p-1">Cañarte®</div>
      </div>
      <p class="text-center my-3">Hola! 👋  I'm Manuel 🤓, a software dev 💻 on the path to mastery 🥋</p>
      <img class="m-auto border-b-48 border-l-8 border-r-8 border-t-8 rounded-md" src="./assets/manny.png" alt="A picture of Manuel">
      <div class="flex justify-between my-3">
        <a href="https://blog.manuelcanarte.com/" target="_blank" class="underline hover:bg-red-500 px-3 rounded-full">Blog</a>
        <a href="https://github.com/macv93" target="_blank" class="underline hover:bg-red-500 px-3 rounded-full">Github</a>
        <a href="https://www.instagram.com/spuddy_raspaspa/" target="_blank" class="underline hover:bg-red-500 px-3 rounded-full">Instagram</a>
        <a href="https://www.linkedin.com/in/manuel-canarte/" target="_blank" class="underline hover:bg-red-500 px-3 rounded-full">Linkedin</a>
      </div>
    </div>
    <footer class="my-3 text-center text-white">️Cañarte © {{ new Date().getFullYear() }}</footer>
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

