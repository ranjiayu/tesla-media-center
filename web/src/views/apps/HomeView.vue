<script setup lang="ts">
import { ref, onMounted, reactive, shallowRef, onUnmounted, computed } from 'vue';
import { get } from '@/functions/requests'

const state = reactive({
  iframeUrl: '',
})

// function fetchConfig() {
//   get(`/api/config`, '读取配置失败')
//     .then(data => {
//       state.iframeUrl = "baidu.com"
//     });
// }

onMounted(() => {
  // fetchConfig();
})
</script>


<template>
  <h1>Welcome</h1>
</template>


<style>
.home-iframe {
  width: 100%;
  height: 100%;
}
</style>