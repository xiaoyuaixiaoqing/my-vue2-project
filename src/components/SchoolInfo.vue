<template>
  <div>
    {{schoolName}}{{schoolName}}
    {{schoolAddress}}{{schoolAddress}}
  </div>
</template>

<script>
export default {
  name: "SchoolInfo",

  data() {
    return {
      schoolName:'商洛学院',
      schoolAddress:'陕西省商洛市'

    }
  },

  methods: {},

  created: {},
}
</script>

<style scoped>

</style>