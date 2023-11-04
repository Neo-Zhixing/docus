<template>
  <DocsPageLayout :page="page">
    <slot />
  </DocsPageLayout>
</template>

<script setup lang="ts">
const { page } = useContent()
</script>
