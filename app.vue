<template>
  <div>
    <!-- <div>{{ runtimeConfig }}</div> -->

    <div>{{ appConfig }}</div>

    <NuxtWelcome />
  </div>
</template>
<script setup>
const runtimeConfig = useRuntimeConfig();
const appConfig = useAppConfig();
</script>
