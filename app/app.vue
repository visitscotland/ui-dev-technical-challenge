<script setup>
  import { createPinia } from 'pinia'
  import { createApp } from 'vue'
  import App from './App.vue'
  import {
    VsHeading,
    VsGrid,
    VsRow,
    VsCol,
    VsCard,
    VsImg,
  } from '@visitscotland/component-library/components';

  const pinia = createPinia()
  const app = createApp(App)
  app.use(pinia)
</script>

<template>
  <div>
    <VsHeading headingStyle="heading-l">UI Developer technical challenge</VsHeading>
  </div>
</template>

<style>
  img {
    max-width: 100%;
  }
</style>
