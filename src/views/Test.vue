<template>
  <div @click="clickFn">1</div>
  <div>2</div>
  <img src="ff" />
</template>
<script lang="ts" setup>
import _ from 'loadsh'
const clickFn = () => {
  const a = 'fd'
  const b = 'aaa'
  a = '复制'
  console.log(a, 'sdfsd====')
}
</script>
