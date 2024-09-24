<template>
  <el-button plain @click="centerDialogVisible = true">
    Click to open the Dialog
  </el-button>

  <el-dialog
    v-model="centerDialogVisible"
    title="Warning"
    width="500"
    align-center
  >
    <span>Open the dialog from the center from the screen</span>
    <template #footer>
      
    </template>
  </el-dialog>
</template>
<script lang="ts" setup>
import { ref } from 'vue'

const centerDialogVisible = ref(false)
</script>
