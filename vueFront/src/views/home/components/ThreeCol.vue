<template>
    <div class="grid-container">
      <div class="one-row">
        <!-- Content for the first row -->
        Row 1
      </div>
      <div class="two-row">
        <!-- Content for the second row -->
        Row 2
      </div>
      <div class="three-row">
        <!-- Content for the third row -->
        Row 3
      </div>
    </div>
  </template>
  
  <style scoped>
  .grid-container {
    display: grid;
    grid-template-rows: 1fr 1fr 1fr; /* Divide into three rows, adjust heights as needed */
    height: 100vh; /* Set the overall height as needed */
  }
  
  .one-row {
    background: #3498db;
    padding: 20px;
    text-align: center;
  }
  
  .two-row {
    background: #2ecc71;
    padding: 20px;
    text-align: center;
  }
  
  .three-row {
    background: #e74c3c;
    padding: 20px;
    text-align: center;
  }
  </style>
  