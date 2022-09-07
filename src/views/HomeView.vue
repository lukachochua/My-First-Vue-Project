<script setup>
  import { useFlash } from '@/composables/useFlash';

  let { flash } = useFlash();
  
  
  
</script>

<template>
  <main>
    <button @click="flash('Test','It Works')">Click Me</button>
  </main>
</template>
