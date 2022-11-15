<template>
  <div>
    <div>{{ runtimeConfig }}</div>

    <div>{{ appConfig }}</div>

    <!-- <NuxtWelcome /> -->
  </div>
</template>
<script setup>
const runtimeConfig = useRuntimeConfig();
const appConfig = useAppConfig();

useHead({
  title: '中文',
  meta: [{ name: 'description', content: '12324356' }],
  bodyAttrs: {
    class: 'test',
  },
  script: [{ children: "console.log('Hello world')" }],
});
</script>
