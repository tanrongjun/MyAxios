<template>
  <div id="app"></div>
</template>

<script>
export default {
  name: 'App',
  async mounted() {
    const result = await this.$api.reqList()
    console.log(result)
  },
}
</script>

<style></style>
