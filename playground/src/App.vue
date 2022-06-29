<template>
  <component :is="Icon" v-for="(Icon, key) in icons" :key="key" class="icon" />
  <hr />
  <component
    :is="`RIcon${key}`"
    v-for="key in Object.keys(icons)"
    :key="key"
    class="icon"
  />
</template>

<script lang="ts" setup>
import { icons } from '@ring-ui-vue/icons-vue/global'
</script>

<style>
.icon {
  height: 24px;
  color: #888888;
  margin: 8px;
}
</style>
