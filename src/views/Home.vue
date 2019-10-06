<template>
  <div class="home">
    <Header />
    <Wrapper />
    <Tester />
    <Project />

  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/home/Header.vue'
import Project from '@/components/home/Project.vue'
import Wrapper from '@/components/home/Wrapper.vue'
import Tester from '@/components/Tester.vue'

export default {
  name: 'home',
  components: {
    Header,
    Project,
    Wrapper,
    Tester
  }
}
</script>

<style scoped>
.home{
  margin-top: 10vh;
}
</style>
