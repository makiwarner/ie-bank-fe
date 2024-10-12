<template>
    <div class="home">
      <h1>Welcome to the Bank Application</h1>
      <button @click="goToAccounts">Go to Accounts Page</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomeView',
    methods: {
      goToAccounts() {
        this.$router.push('/accounts');
      }
    }
  };
  </script>
  
  <style scoped>
  .home {
    text-align: center;
    margin-top: 50px;
  }
  button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  button:hover {
    background-color: #45a049;
  }
  </style>
  