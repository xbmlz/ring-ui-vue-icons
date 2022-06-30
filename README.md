# JetBrains Ring UI Icons

[![Unit Test](https://github.com/xbmlz/ring-ui-vue-icons/actions/workflows/unit-test.yml/badge.svg)](https://github.com/xbmlz/ring-ui-vue-icons/actions/workflows/unit-test.yml)
![GitHub Repo stars](https://img.shields.io/github/stars/xbmlz/ring-ui-vue-icons?style=social)
![GitHub forks](https://img.shields.io/github/forks/xbmlz/ring-ui-vue-icons?style=social)


- [`@ring-ui-vue-icons/icons-svg`](https://www.npmjs.com/package/@ring-ui-vue-icons/icons-svg) raw svg files
- [`@ring-ui-vue-icons/icons-vue`](https://www.npmjs.com/package/@ring-ui-vue-icons/icons-vue) vue components

![](https://cdn.jsdelivr.net/gh/xbmlz/static@main/img/202206301021239.png)

## 使用

### 安装

```
# npm
npm install @ring-ui-vue/icons-vue
# Yarn
yarn add @ring-ui-vue/icons-vue
# pnpm
pnpm install @ring-ui-vue/icons-vue
```

### 浏览器直接引入

#### unpkg

```html
<script src="//unpkg.com/@ring-ui-vue/icons-vue"></script>
```
#### jsDelivr

```html
<script src="//cdn.jsdelivr.net/npm/@ring-ui-vue/icons-vue"></script>
```
### 使用

```html
<template>
  <div class="">
    <Ok style="width: 2rem" />
  </div>
</template>

<script lang="ts">
export default { name: "demo" };
</script>

<script setup lang="ts">
import { Ok } from "@ring-ui-vue/icons-vue";
</script>

<style scoped></style>

```
