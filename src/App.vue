<template>
  <h1 class="text-4xl text-blue-700 hover:text-blue-400 transition">
    <router-link to="/">dayjs 練習</router-link>
  </h1>
  <router-view></router-view>
</template>

<script>
export default {
  setup () {
    return {
      title: 'Hello'
    }
  }
}
</script>


<style>
#app {
  font-family: 'openhuninn', 'Noto Sans TC', sans-serif;
  text-align: center;
}
</style>
