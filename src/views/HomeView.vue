<script setup>
import TheWelcome from "@/components/TheWelcome.vue";


let message = $ref("Hello World!");

let doSomething = () => {
  alert("Doing it now");
};



</script>

<template>
  <main>
    <TheWelcome />

    <p>{{ message }}</p>


    <p>
      <button @click="doSomething">Click me</button>
    </p>
  </main>
</template>
