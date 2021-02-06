<template>
  <div class="flex flex-col h-screen bg-black font-mono" id="app">
      <div class="m-auto text-white">
        <h1 class="text-center py-5">Manuel Cañarte</h1>
        <div class="flex justify-between">
          <a href="https://github.com/macv93" class="hover:bg-red-500 px-3" >Github</a>
          <a href="https://www.linkedin.com/in/manuel-canarte/" class="hover:bg-red-500 px-3" >Linkedin</a>
          <a href="https://www.instagram.com/spuddy_raspaspa/" class="hover:bg-red-500 px-3" >Instagram</a>
        </div>
        <img class="m-auto rounded-tl-full rounded-tr-full py-5" src="./assets/manny.png" alt="A picture of Manuel">
        <p clas="text-right">Hola! I'm Manuel, a software dev on the path mastery</p>
      </div>
    <footer class="py-2 text-center text-white">️Cañarte © {{new Date().getFullYear()}}</footer>
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

