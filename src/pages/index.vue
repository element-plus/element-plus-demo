<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})

const name = ref('Element Plus Demo')
</script>

<template>
  <div class="w-screen h-screen flex flex-col items-center justify-center">
    <h1 class="text-lg mb-4">
      {{ name }}
    </h1>
    <div>
      <el-input v-model="name" size="large" clearable class="!w-60" placeholder="please input" />
    </div>
  </div>
</template>
