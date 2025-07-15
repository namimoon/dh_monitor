<template>
  <div></div>
</template>

<script setup lang="ts">

import { onMounted } from 'vue'
import router from './router'

onMounted(() => {
  router.push('/home');
});
</script>

