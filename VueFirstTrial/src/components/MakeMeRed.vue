<template>
    <h1 :class="titleClass">Make me red</h1> <!-- add dynamic class binding here -->
</template>

<script>
    export default {
        data() {
            return {
                titleClass: 'title'
            }
        }
    }
</script>

<style scoped>
    .title {
        color: red;
    }
</style>