<script setup lang="ts">
import { supabase } from './lib/supabaseClient'

console.log(supabase)
</script>

<template>
  <main>
    <Router-view />
  </main>
</template>

<style scoped></style>
