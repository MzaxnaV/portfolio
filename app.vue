<script setup lang="ts">
const appConfig = useAppConfig()

useSeoMeta({
  title: appConfig.title,
  ogTitle: appConfig.title,
  description: 'MzaxnaV\'s Portfolio website.',
  ogDescription: 'MzaxnaV\'s Portfolio website.',
})

</script>

<template>
  <NuxtPage />
</template>

<!-- <style>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style> -->
