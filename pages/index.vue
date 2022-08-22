<template>
  <div>
    <ContentRenderer class="mb-2" :value="page"/>
    <a class="block" href="/other">To Other from Anchor</a>
    <NuxtLink to="/other">To Other From NuxtLink </NuxtLink>
  </div>
</template>

<script lang="ts" setup>
const { page } = useContent();
</script>
