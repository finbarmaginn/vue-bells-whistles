<template>
  <div class="finbar" id="finbar">
    <h1>Finbar Maginn is my name...</h1>
    <h2>I added this page as an experiment and to get used to using Vue.</h2>
    <button v-on:click="clickExample">Click Me</button>
  </div>
</template>

<script>
  export default {
    name: "finbar",
    methods: {
      clickExample(){
        alert("clicked");
      }
    }
  }
</script>

<style>
  #finbar button {
    background: none;
    border-radius: 0;
    border: solid 1px #e6e6e6;
    padding: 5px;
    margin: 0;
    cursor: pointer;
  }
</style>
