<template>
  <div>
    <div class="flex flex-row content-evenly lg:font-mono">
      <div class="absolute inset-y-0 left-0 ml-5 my-5 text-9xl">M.</div>
      <div class="text-2xl absolute inset-y-0 right-0 py-5 px-5 ">
        <a href="#" class="text-2xl mr-5 hover:bg-red-600 hover:text-white">About</a>
        <a href="#" class="transform rotate-45 hover:bg-red-500 hover:text-white">Photography</a>
        <a href="#" class="transform rotate-45 hover:bg-red-500 hover:text-white">Photography</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    name: String
  }

}
</script>
