<template>
    <div class="bg-blue-100 border mb-2 px-8 text-right w-full">
        <span>{{screenValue}}</span>
    </div>
</template>

<script>
export default {
    name: 'Screen',
    props: {
        screenValue: Number,
    },
    data() {
        return {
            result: 0,
        }
    },
}
</script>

<style>

</style>