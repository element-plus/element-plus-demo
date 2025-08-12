<script setup lang="ts" generic="T extends any, O extends any">
defineOptions({
  name: 'IndexPage',
})

const name = ref('Element Plus Demo')
</script>

<template>
  <Main>
    <h1 class="text-lg mb-4">
      {{ name }}
    </h1>
    <div>
      <el-button type="primary" size="large" class="mr-4" @click="toggleDark()">
        {{ isDark ? 'Light Mode' : 'Dark Mode' }}
      </el-button>
      <el-input v-model="name" size="large" clearable class="!w-60" placeholder="please input" />
    </div>
  </Main>
</template>
