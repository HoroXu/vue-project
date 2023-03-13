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
  a = '测试验证校验'
  console.log(a, 'sdfsd====')
}
</script>
