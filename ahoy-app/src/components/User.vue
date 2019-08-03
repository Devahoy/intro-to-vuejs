<template>
  <div class="user">
    <h2>{{ name }}</h2>
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: 'User',
    props: {
      name: String
    }
  }
</script>

<style>

</style>