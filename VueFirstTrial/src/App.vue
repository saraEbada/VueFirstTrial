<template>
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <!--<HelloWorld msg="Welcome to Your Vue.js App" />-->
    <MakeMeDynamic />
    <MakeMeRed />
    <CounterIncrement />
</template>

<script>
    //import HelloWorld from './components/HelloWorld.vue'
    import MakeMeDynamic from './components/MakeMeDynamic.vue'
    import MakeMeRed from './components/MakeMeRed.vue'
    import CounterIncrement from './components/CounterIncrement.vue'

    export default {
        name: 'App',
        components: {
            MakeMeDynamic,
            MakeMeRed,
            CounterIncrement
        }
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>