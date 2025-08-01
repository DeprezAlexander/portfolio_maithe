<template>
  <span class="font-black text-3xl">{{ title }}</span>
  <span class="text-gray-700" :class="{ 'w-10/12': cappedWidth }">
    {{ description }}<br /><i class="text-sm">{{ info }}</i>
  </span>
</template>
<script setup lang="ts">
interface Props {
  title: string
  description: string
  info: string
  cappedWidth?: boolean
}

withDefaults(defineProps<Props>(), {
  cappedWidth: true,
})
</script>
