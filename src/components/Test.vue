<template>
  <div class="t">{{ message }}</div>
</template>

<script>
export default {
  name: 'Test',
  data() {
    return {
      message: `Seems simple enough... ${this.$route.params.m}`,
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.t {
  font-size: 25px;
  color: red;
}
</style>
