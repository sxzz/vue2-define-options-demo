<script setup lang="ts">
import { ref } from '@vue/composition-api'

defineOptions({
  name: 'Hello',
})

const msg = ref('')
</script>

<template>
  <div>
    <h1>Hello World</h1>
    <h2>{{ msg }}</h2>
    <input v-model="msg" type="text" />
  </div>
</template>
