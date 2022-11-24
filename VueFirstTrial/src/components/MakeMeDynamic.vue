<template>
    <h1>{{ message }}</h1>
    <h1>{{ message.split('').reverse().join('') }}</h1>
</template>

<script>
    export default {
        data() {
            return {
                message: 'Hello World!'
            }
        }
    }
</script>

<style scoped>
</style>