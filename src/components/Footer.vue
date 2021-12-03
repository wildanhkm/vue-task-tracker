<template>
  <footer>
    <p>Copyright Wildan Hakim &copy; 2021</p>
    <router-link to="/about">About</router-link>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer {
  margin-top: 20px;
  text-align: center;
}
a {
  color: #333;
}
</style>
