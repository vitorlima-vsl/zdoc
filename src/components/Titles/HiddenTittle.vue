<script setup lang="ts">

defineProps<{
    title: string
    color: 'WHITE' | 'BLACK'
}>()
</script>

<template>
    <span 
        class="text-8xl font-black text-transparent uppercase absolute top-10 left-1/2 text-nowrap -translate-x-1/2 select-none"
        :class="{ 'stroke-white': color?.toUpperCase() === 'WHITE', 'stroke-black': color?.toUpperCase() === 'BLACK' }"
    >
        {{ title }}
    </span>
</template>

<style scoped>
.stroke-white {
    -webkit-text-stroke: 1px rgba(255, 255, 255, 0.164);
}
.stroke-black {
    -webkit-text-stroke: 1px rgba(0, 0, 0, 0.164);
}
</style>