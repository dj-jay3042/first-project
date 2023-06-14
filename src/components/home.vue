<template>
    <h1>Home Component</h1>
    <button v-on:click="test()">Click to see magic!!!</button>
</template>
<script>
export default {
    name: "HomeFile"
}
</script>

<style scoped>
h1{
    color:crimson;
}
</style>