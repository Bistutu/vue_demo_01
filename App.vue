<template>
  <div>
    <school></school>
    <student></student>
  </div>
</template>

<script>
import school from "./school.vue";
import Student from "./student.vue";
export default {
  template: `
    <App></App>
    `,
  components: { school, Student },
};
</script>

<style>
</style>