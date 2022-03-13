<template>
  <div>
    <h1>OLA</h1>
    <p>{{ texto }}</p>
  </div>
</template>

<script>
export default {
  props: ["texto"],
};
</script>

<style>
h1 {
  color: red;
}
p {
  color: orange;
}
</style>
