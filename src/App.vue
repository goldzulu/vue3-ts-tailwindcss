<template>
  <div>
    <div class="flex">
      <img class="block mx-auto" alt="Vue logo" src="./assets/logo.png" />
    </div>
    <HelloWorld msg="Welcome to Your Vue 3 + TypeScript + TailwindCSS BoilerPlate" />
  </div>
</template>

<script lang="ts">
import "tailwindcss/tailwind.css";
import { defineComponent } from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default defineComponent({
  name: "App",
  components: {
    HelloWorld
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
