<script setup>
  import { useMonitor } from '@/composables/monitor';

  const { menu } = useMonitor();
</script>

<template>
  <div>
    <component :is="menu" />
    <main>
      <router-view />
    </main>
    <footer>
      <p>Copyright &copy; 2024</p>
    </footer>
  </div>
</template>