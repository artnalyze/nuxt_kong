<template>
  <div>
    <h1>Welcome : {{ $route.params.id }}</h1>
  </div>
</template>

<script>
export default {
  validate(data) {
    return /^[A-Za-z]+$/.test(data.params.id)
    // validate url only string
  }
}
</script>

<style scoped></style>
