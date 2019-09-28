<template>
   <div>
        <div class="mb-2 w-full">
            <button class="btn"> ( </button>
            <button class="btn"> ) </button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn"> * </button>
            <button class="btn"> / </button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn"> + </button>
            <button class="btn"> - </button>
        </div>
        <div class="mb-2 w-full">
            <button class="btn"> Back </button>
        </div>
   </div>
</template>

<script>
export default {
    name: 'basicMathButtons',
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