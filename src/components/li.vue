<template>
  <el-input
    placeholder="请输入内容"
    v-model="input"
    :disabled="true">
  </el-input>
</template>

<script>
  export default {
    data() {
      return {
        input: ''
      }
    }
  }

</script>

<style>
</style>
