<template>
  <div>
    <!-- here nuxt will replace page content -->
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "login",
});
</script>
