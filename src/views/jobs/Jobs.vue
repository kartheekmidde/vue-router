<template>
  <h1>Jobs</h1>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{ job.title }}</h2>
  </div>
</template>

<script>
export default {
  name: "Jobs",
  data() {
    return {
      jobs: [
          { title: 'UX Developer', id: 1, details: 'test' },
          { title: 'Web Developer', id: 2, details: 'test' },
          { title: 'Vue Developer', id: 3, details: 'test' },
        ]
    }
  }
}
</script>

<style scoped>

</style>