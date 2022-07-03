<template>
  <div>
    <span>
      <button>{{message}}</button>
    </span>
  </div>
</template>

<script>
export default {
  name: "your-component",
  data: {
    message: "click this button"
  }
}
</script>

<style scoped>
  span{
    font-size: 1.2em;
  }
</style>