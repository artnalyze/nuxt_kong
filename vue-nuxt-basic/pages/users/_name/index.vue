<template>
  <div>
    <h1>Welcome : {{ $route.params.name }}</h1>
  </div>
</template>

<script>
export default {
  validate(data) {
    return /^\d+$/.test(data.params.name)
    // validate url only number
  }
}
</script>

<style scoped></style>
