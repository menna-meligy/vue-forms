<template>
  <nav class="navbar">
    <router-link to="/">Home</router-link> |
    <router-link to="/login">Login</router-link>
  </nav>
</template>

<script>
export default {
  name: "AppNavbar",
};
</script>

<style scoped>
.navbar {
  background-color: #333;
  padding: 10px;
}
.navbar a {
  color: white;
  text-decoration: none;
  margin: 0 10px;
}
</style>
