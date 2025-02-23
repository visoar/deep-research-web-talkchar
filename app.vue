<template>
  <UApp :locale="zh_cn">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </UApp>
</template>

<script setup lang="ts">
  import { zh_cn } from '@nuxt/ui/locale'

  // TODO
  useHead({
    title: 'Deep Research Web UI',
    script: [
      // Anonymous analytics
      {
        defer: true,
        src: 'https://track.pixmiller.com/script.js',
        'data-website-id': '8b7ae8a3-6275-42fa-8787-e16c5417b003',
      },
    ],
  })
</script>
