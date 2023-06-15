<template>
    <h1>Home Component</h1>
    <h2>{{ count }}</h2>

    <button v-on:click="test()">Increment</button><br>
    
    <button v-on:dblclick="test('button2')">Click to see magic!!!</button>
</template>
<script>
export default {
    name: "HomeFile",
    data() {
        return {
            count : 0
        }
    },
    methods: {
        test() {
            this.count++;
        },
        getConsole() {
            alert("sjhgcflhguy");
        }
    }
}
</script>

<style scoped>
h1{
    color:crimson;
}
</style>