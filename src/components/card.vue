<template>
  <div class="rounded-md shadow-md w-11/12 mx-auto py-10 lg:w-3/12 mb-4 font-sans">
    <h3 class="text-2xl text-gray-800">基礎用法</h3>
    <p class="text-base text-gray-800 bg-gray-300">day().format()</p>
    <p class="text-base text-gray-800">{{time}}</p>
  </div>
</template>

<script>
import day from 'dayjs'
export default {
  setup () {
    return {
      time: day().format()
    }
  }
}
</script>