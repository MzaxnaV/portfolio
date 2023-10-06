<script setup lang="ts">
const appConfig = useAppConfig()
</script>

<template>
  <div>
    {{ appConfig.title }}
    <NuxtWelcome />
  </div>
</template>
