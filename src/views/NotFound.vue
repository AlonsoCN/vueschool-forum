<template>
  <div>
    <h1>Page Not Found</h1>
    <p>
      Oops, we couldn't find what you were looking for. Why don't you
      <router-link :to="{ name: 'Home'}">
        go home instead
      </router-link>
    </p>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
  h1 {
    font-size: 100px;
  }
  p {
    font-size: 50px;
    font-weight: 100;

  }
</style>
