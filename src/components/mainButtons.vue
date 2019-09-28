<template>
   <div class="mr-2">
        <div class="mb-2 w-full">
            <button class="btn" @click="buttonClick(7)">7</button>
            <button class="btn" @click="buttonClick(8)">8</button>
            <button class="btn" @click="buttonClick(9)">9</button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn" @click="buttonClick(4)">4</button>
            <button class="btn" @click="buttonClick(5)">5</button>
            <button class="btn" @click="buttonClick(6)">6</button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn" @click="buttonClick(1)">1</button>
            <button class="btn" @click="buttonClick(2)">2</button>
            <button class="btn" @click="buttonClick(3)">3</button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn" @click="buttonClick(0)">0</button>
            <button class="btn" @click="buttonClick('clr')">.</button>
            <button class="btn" @click="buttonClick('ent')">=</button>
        </div>
   </div>
</template>

<script>
export default {
    name: 'mainButtons',
    props: {

    },
    data() {
        return {
            
        }
    },
    methods: {
        buttonClick(value) {
            if (!isNaN(value)) {
                this.$emit('input', value);
            }
        }
    }
}
</script>

<style lang="less">
    .btn{
        @apply bg-blue-500 text-white font-bold mx-2 py-2 px-4 rounded;
    }
</style>