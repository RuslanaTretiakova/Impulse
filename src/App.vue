<script setup lang="ts">
import { supabase } from './lib/supabaseClient'

console.log(supabase)
</script>

<template>
  <h1>Hello</h1>
  <main>
    <Router-view />
  </main>
</template>

<style scoped></style>
