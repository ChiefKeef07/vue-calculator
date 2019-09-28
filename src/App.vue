<template>
  <div class="flex justify-center mt-8 w-full">
    <div class="border border-gray-300 flex justify-center rounded shadow-md w-1/2">
      <Screen></Screen>
    </div>
  </div>
</template>

<script>
import Screen from './components/Screen.vue';

export default {
  name: 'app',
  components: {
    Screen,
  }
}
</script>

<style>

</style>
