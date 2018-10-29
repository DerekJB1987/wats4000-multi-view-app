<template>
  <div class="component">
    <h1>{{ message }}</h1>
    <ul>
      <li><router-link to="Home">Home</router-link></li>
      <li><router-link to="Survey">Survey</router-link></li>
    </ul>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        message: 'Always use your Developer debugging tools with your web apps'
      }
    }
  }
</script>

<style scoped>
  .component {
    background: #ffffff;
    min-height: 400px;
  }
</style>