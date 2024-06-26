<template>
  <div>
    <n-avatar
      round
      size="small"
      src="nonexistent.png"
    >
      <template #fallback>
        Me
      </template>
    </n-avatar>
  </div>
</template>

<script setup lang="ts">
import { NAvatar } from 'naive-ui';
</script>
