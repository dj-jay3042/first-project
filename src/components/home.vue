<template>
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
      chk: ["Jay", "Chauhan"],
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
}
</style>
