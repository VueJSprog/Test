<template>
    <div class="special">
        // put HTML here
        <br>
        <button @click="methodClicked()" style="btn btn-green">ButtonClicked</button>
    </div>
</template>

<script>
export default {
    name: 'DemoView',
    components: {
    },
    props: {
    },
    methods: {
        methodClicked() {
            alert('You have clicked the button')
        },
    },
    mounted() {
        console.log('Demo mounted') // 0
    }
}
</script>

<style>
#special {
    text-decoration: line-through;
}
/* Put the additionnal style here  */
</style>