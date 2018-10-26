<template>
  <div class="component">
    <h2>{{ message }}</h2>
  </div>
</template>

<script>
  export default {
    data () {
      return {
        message: 'Always use Inspect on your web apps'
      }
    }
  }
</script>

<style scoped>
  .component {
    background: #e8e8e8;
    min-height: 400px;
  }
</style>