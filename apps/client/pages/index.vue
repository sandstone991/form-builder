<script setup lang="ts">
import BaseEditor from '../editor/prosemirror/BaseEditor.vue';
</script>

<template>
  <div class="w-full h-full">
    <Suspense>
      <ClientOnly>
      </ClientOnly>
    </Suspense>
    <InputEntry />
  </div>
</template>
