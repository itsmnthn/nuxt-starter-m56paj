<script lang="ts" setup>
import '~~/asset/css/main.css';
</script>

<template>
  <div id="layout" class="flex flex-col">
    <Html lang="en"></Html>
    <main class="flex-grow">
      default layout
      <slot />
    </main>
  </div>
</template>
