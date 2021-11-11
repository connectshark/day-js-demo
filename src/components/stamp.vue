<template>
  <div class="rounded-md shadow-md w-11/12 mx-auto py-10 lg:w-3/12 mb-4 font-sans">
    <h3 class="text-2xl text-gray-800">時間帶入</h3>
    <p class="text-base text-gray-800 bg-gray-300">day(1635327948129).format()</p>
    <p class="text-base text-gray-800">{{time}}</p>
  </div>
</template>

<script>
import day from 'dayjs'
export default {
  setup () {
    return {
      time: day(1635327948129).format()
    }
  }
}
</script>