<template>
  <h2 class="text-2xl">第一頁由此開始</h2>
  <p>{{time}}</p>
</template>

<script>
import Day from 'dayjs'
export default {
  setup () {
    return {
      time: Day().format()
    }
  }
}
</script>

<style lang="scss" scoped>
</style>