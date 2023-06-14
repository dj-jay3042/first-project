<template>
<<<<<<< HEAD
  <h1>Home Component</h1>
  Sing : <input type="checkbox" name="hobby" value="Sing" v-model="chk" /><br />
  Dance :
  <input type="checkbox" name="hobby" value="Dance" v-model="chk" /><br />
  <button v-on:click="getData()">Get Values</button>

  <h3>Select Values : {{ chk }}</h3>
</template>
<script>
export default {
  name: "HomeFile",
  data() {
    return {
      chk: [],
    };
  },
  methods: {
    getData() {
      alert("Email: " + this.email + "\nPassword: " + this.passwd);
    },
  },
};
</script>

<style scoped>
h1 {
  color: crimson;
=======
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
>>>>>>> 0177faeb27c469160f08e32a4132dd489aec9d2a
}
</style>