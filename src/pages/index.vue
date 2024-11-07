<script setup lang="ts"></script>

<template>
  <RouterLink :to="{ name: '/projects/[id]', params: { id: 1 } }"
    >Go to project 1</RouterLink
  >
</template>
