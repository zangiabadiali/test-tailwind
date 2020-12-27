<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div class="md:container mx-auto md:px-4">
    <div class="block bg-blue-100 w-56 h-56" />
    <div class="block bg-blue-100 w-56 h-56" />
    <div class="block bg-blue-100 w-56 h-56" />
    <h1>test</h1>
    <ul class="list-disc list-inside">
      <li>One</li>
      <li>Two</li>
      <li>Three</li>
    </ul>
  </div>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style></style>
