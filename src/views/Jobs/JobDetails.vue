<template>
  <h1>Job Details Page</h1>
  <p>The job id is {{ $route.params.id }}</p>
</template>

<script>
export default {
  // if you use props you dont need to use data()
  props: ["id"],
  //   data() {
  //     return {
  //       id: this.$route.params.id,
  //     };
  //   },
};
</script>

<style></style>
