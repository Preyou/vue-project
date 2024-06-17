<script setup>
import {NTabs,NTabPane} from 'naive-ui'
import {ref} from 'vue'

const name = ref('aaaa')
</script>

<template>
<input v-model="name"></input>
<NTabs style="width:100vw;height:100vh" placement="left" type="card" closable addable>
  <template #prefix>
      Prefix
  </template>
  <NTabPane name="a" tab="a">
    <template #tab>
    {{name}}
    </template>
  </NTabPane>
  <template #suffix>
      Suffix
  </template>
</NTabs>
</template>
