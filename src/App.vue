<template>
  <div class="flex justify-center mt-8 w-full">
    <div class="border border-gray-300 flex flex-wrap p-6 rounded shadow-md w-1/2">
      <Screen :screenValue="screenValue"></Screen>
      <mainButtons @input="updateScreen"></mainButtons>
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
  },
  data() {
    return{
      screenValue: 0,
    }
  },
  methods: {
    updateScreen(val) {
      this.screenValue = (this.screenValue*10) + val;
    }
  }
}
</script>

<style>

</style>
