<docs>
---
title: 输入框组件
---
这是一个`input`组件的使用Demo
</docs>

<script setup lang="ts">
import { ref } from 'vue'

const value = ref('')
</script>

<template>
  <div>
    输入信息:{{ value }}
    <!-- <TovInput v-model="value" disabled /> -->
    <TovInput v-model="value" />
    <!-- <TovInput /> -->
  </div>
</template>
