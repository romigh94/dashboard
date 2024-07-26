<template>
    <div class="dashboard p-3">
      <h2>Dashboard Content</h2>
      <ChartComponent />
    </div>
  </template>
  
  <script>
  import ChartComponent from './ChartComponent.vue';
  
  export default {
    components: {
      ChartComponent,
    },
  };
  </script>
  
  <style scoped>
  .dashboard {
    flex-grow: 1;
    padding: 20px;
  }
  </style>
  