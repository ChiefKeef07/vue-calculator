<template>
   <div class="w-1/2">
        <div class="mb-2 w-full">
            <button class="btn">7</button>
            <button class="btn">8</button>
            <button class="btn">9</button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn">4</button>
            <button class="btn">5</button>
            <button class="btn">6</button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn">1</button>
            <button class="btn">2</button>
            <button class="btn">3</button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn">0</button>
            <button class="btn">Clr</button>
            <button class="btn">Ent</button>
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
}
</script>

<style lang="less">
    .btn{
        @apply bg-blue-500 text-white font-bold mx-2 py-2 px-4 rounded;
    }
</style>