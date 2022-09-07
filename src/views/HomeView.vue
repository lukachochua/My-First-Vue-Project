<script setup>

import { useStorage } from '@/composables/useStorage.js';

  let food = useStorage('food', 'tacos');
  let age = useStorage('age', '10');
</script>

<template>
  <main>
    <p>
      What is your favorite food? <input type="text" v-model="food">
    </p>

    <p>
      What is your age? <input type="text" v-model="age">
    </p>
  </main>
</template>
