<template>
  <div class="h-screen flex flex-col">
    <div class="p-2 my-2 rounded-full hover:bg-blue-50 w-min dark:hover:bg-white/20" :class="defaultTransition">
      <NuxtLink to="/about">
        <div class="w-8 h-8">
          <LogoTwitter/>
        </div>
      </NuxtLink>
    </div>
  </div>
</template>

<script setup lang="ts">

const { defaultTransition } = useTailwindConfig();

</script>

<style scoped>

</style>