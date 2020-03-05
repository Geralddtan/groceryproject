<template>
    <div>
        <button v-on:click = "counter+=1"> + </button>
        <button v-on:click = "counter-=1"> - </button>
        <br>
        <h3> Total Count: {{counter}} </h3>
    </div>
</template>

<script>
export default {
    data() {
        return{
            counter: 0
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
button {
  font-family: "Avenir";
  text-align: center;
  color: #193;
}
h3 {
  font-family: "Avenir";
  text-align: center;
  color: #499;
}
</style>