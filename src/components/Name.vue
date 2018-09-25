<template>
  <div class="name">
    <h1>Hello {{ their_name }}.</h1>
  </div>
</template>

<script>
export default {
  name: 'Name',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>