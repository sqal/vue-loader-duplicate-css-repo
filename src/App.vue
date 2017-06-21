<template>
  <div id="app">
    <comp-a></comp-a>
    <comp-b></comp-b>
  </div>
</template>

<script>
  import CompA from './components/A/A';
  import CompB from './components/B/B';

  export default {
    name: 'app',
    components: {
      CompA,
      CompB,
    },
  };
</script>
