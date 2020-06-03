<template>
  <div>
    <h1>Welcome : {{ $route.params.id }}</h1>
  </div>
</template>

<script>
export default {
  validate(data) {
    return /^\d+$/.test(data.params.id)
    // validate url only number
  }
}
</script>

<style scoped></style>
