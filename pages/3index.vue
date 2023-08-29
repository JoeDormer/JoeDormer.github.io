<template>
	<div class="my-component">
	  <h1>{{ greeting }}</h1>
	  <p>This is a basic Vue.js component.</p>
	</div>
  </template>
  
  <script>
  export default {
	data() {
	  return {
		greeting: "Hello, Vue!"
	  };
	}
  };
  </script>
  
  <style>
  .my-component {
	font-family: Arial, sans-serif;
	background-color: #f0f0f0;
	padding: 20px;
	border: 1px solid #ccc;
	border-radius: 5px;
	box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }
  
  h1 {
	color: #333;
  }
  
  p {
	color: #666;
  }
  </style>
  