<template>
  <div>
    <div>Play Page</div>
    <NuxtLink to="/"> Home Page </NuxtLink>
  </div>
</template>

<script>
export default {
  created() {
    console.log(this.$route.path)
  },
}
</script>

<style lang="scss" scoped>
</style>