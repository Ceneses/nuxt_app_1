<template>
  <div :class="{'dark': darkMode}">
  </div>
</template>

<script setup lang="ts">
import {ref} from "vue";

const darkMode = ref(false)
</script>