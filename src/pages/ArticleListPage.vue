<template>
  <TitleBar>게시물 리스트</TitleBar>
  <input type="checkbox">
  <input type="radio">
  <input type="radio">
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import TitleBar from '../components/TitleBar.vue'

export default defineComponent({
  components: { TitleBar },
  name: 'AppListPage',
})
</script>

<style scoped>

</style>
