<script lang="ts" setup>
const props = defineProps<{ label: string }>();
</script>

<template>
  <div class="flex flex-col items-center space-y-2">
    <button class="bg-gray-200 hover:bg-gray-300 p-3 rounded-full w-14 h-14 flex items-center justify-center">
      <slot>
        <IconQuestion />
      </slot>
    </button>
    <span class="font-semibold text-sm">{{ props.label }}</span>
  </div>
</template>
