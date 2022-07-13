<template>
  <KButton v-bind="$attrs">
    <slot></slot>
  </KButton>
</template>
<script setup >
import { Button as KButton } from "@progress/kendo-vue-buttons";
</script>