<template>
    <Label :text="test"/>

</template>

<script>
export default {
  props: {
      test: { type: String, default: 'peter' }
  },
  data() {
      return {

      }
  },

}
</script>

<style scoped>

</style>