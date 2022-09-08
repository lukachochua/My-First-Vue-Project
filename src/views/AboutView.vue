<script setup>
  import { useFlash } from '@/composables/useFlash';
  let { flash } = useFlash();
  
  
  
</script>

<template>
  <div>
    <p>
      About Page. the current count is {{ counter.count }}
    </p>
  </div>
</template>


