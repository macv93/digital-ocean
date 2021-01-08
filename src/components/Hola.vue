<template>

  <div class="inline-block align-baseline m-auto px-10">

    <div class="inline-block align-baseline">
      <h1 class="text-center text-purple-600">{{ name }}</h1>
      <img class="rounded-full" alt="manny" src="../assets/manny.png">
    </div>

    <blockquote>
      <p>
        Hello there! 👀
        My name is Manuel but most people call me Manny,
        After working in non-tech roles for about 3 years, I decided to return to post-secondary and learn how to code.
        I now call myself a software developer.
      </p>
    </blockquote>
    <ul>
      <li><strong>Programming:</strong> C, PHP, JavaScript,</li>
      <li><strong>Web:</strong> HTML/CSS/JS, Laravel, Vue, React</li>
      <li><strong>Languages:</strong> Fluent Spanish 🇨🇴 and French 🇨🇦</li>
    </ul>

    <p>I'm currently working at <a href="https://vehikl.com/">Vehikl</a> with some pretty cool peeps</p>
    <p>
      Please visit my <a href="https://www.linkedin.com/in/manuel-canarte/">LinkedIn</a> to learn more about my
      professional experience.
    </p>
    <div class="inline-block align-baseline">
      <p class="text-center">© Manuel Cañarte {{ formatTime(Date.now()) }}</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hola',
  props: {
    name: String
  },
  methods: {
    formatTime: function (time) {
      const currentTime = new Date(time)
      return currentTime.toDateString();
    }
  }
}
</script>
