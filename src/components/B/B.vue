<template>
  <div>
    <p class="b">component B</p>
    <b1></b1>
    <b2></b2>
  </div>
</template>

<script>
  import B1 from './B1';
  import B2 from './B2';
  import './B.css';

  export default {
    name: 'B',
    components: {
      B1,
      B2,
    },
  };
</script>

