<script setup>
import { useLayout } from '@/composables/monitor';
const { layout } = useLayout();
</script>
<template>
    <component :is="layout" />
</template>