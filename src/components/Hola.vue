<template>
  <div class="hello">
    <h1>{{ name }}</h1>
    <pre>
      Hello there! 👀
      My name is Manuel but most people call me Manny,
      After working in non-tech roles for about 3 years, I decided to return to schools and learn how to code.
      Please visit my <a href="https://www.linkedin.com/in/manuel-canarte/">LinkedIn</a> to learn more about my professional experience.
      I now call myself a software developer.
      <strong>Programming:</strong> C, PHP, JavaScript,
      <strong>Web:</strong> HTML/CSS/JS, Laravel, Vue, React
      <strong>Languages:</strong> Fluent Spanish 🇨🇴 and French 🇨🇦
    </pre>
    <p>I'm currently working at <a href="https://vehikl.com/">Vehikl</a> with some pretty cool peeps</p>
  </div>
</template>

<script>
export default {
  name: 'Hola',
  props: {
    name: String
  }
}
</script>
