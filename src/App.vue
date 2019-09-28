<template>
  <div class="flex justify-center mt-8 w-full">
    <div class="border border-gray-300 flex flex-wrap p-6 rounded shadow-md w-1/2">
      <Screen></Screen>
      <mainButtons></mainButtons>
      <basicMathButtons></basicMathButtons>
    </div>
  </div>
</template>

<script>
import basicMathButtons from './components/basicMathButtons';
import mainButtons from './components/mainButtons.vue';
import Screen from './components/Screen.vue';

export default {
  name: 'app',
  components: {
    basicMathButtons,
    mainButtons,
    Screen,
  }
}
</script>

<style>

</style>
