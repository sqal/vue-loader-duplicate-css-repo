<template>
  <div>
    <p class="a">component A</p>
    <a1></a1>
    <a2></a2>
  </div>
</template>

<script>
  import A1 from './A1';
  import A2 from './A2';

  export default {
    name: 'A',
    components: {
      A1,
      A2,
    },
  };
</script>

<style src="./A.css"></style>
