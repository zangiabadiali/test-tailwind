<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div class="md:container mx-auto md:px-4">
    <AppTexInput />
  </div>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import AppTexInput from './components/AppTextInput.vue'
export default {
  name: "App",
  components: {
    AppTexInput
  },
};
</script>

<style></style>
