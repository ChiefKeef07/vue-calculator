<template>
    <div>
        <div>
            <input type="number" v-model="number"/>
        </div>
        <div>
            <span>{{result}}</span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Screen',
    props: {

    },
    data() {
        return {
            number: 0,
            result: 0,
        },
    },
}
</script>

<style>

</style>