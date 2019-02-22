<template>
  <hooper>
    <slide>
      <h1>Slide 1</h1>
    </slide>
    <slide>
      <h1>Slide 2</h1>
    </slide>
    <slide>
      <h1>Slide 3</h1>
    </slide>
  </hooper>
</template>

<script>
  import {Hooper, Slide} from 'hooper';

  export default {
    name: "App",
    components: {
      Hooper,
      Slide
    }
  }
</script>
