<script setup>
const test = 'text-red-500'
</script>

<template>
  <p
    class="flex relative"
    :class="test"
  >
    TEST 1
  </p>
  <p :class="`flex relative ${test}`">
    TEST 1
  </p>
</template>
