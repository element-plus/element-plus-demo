<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})

const name = ref('')
</script>

<template>
  <div class="w-screen h-screen flex items-center justify-center">
    <el-input v-model="name" class="mt-10 !w-60" placeholder="please input" />
  </div>
</template>
