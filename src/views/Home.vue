<template>
  <div class="home">
    <Header />
    <Wrapper />
    <Projects />

  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/home/Header.vue'
import Projects from '@/components/Projects.vue'
import Wrapper from '@/components/home/Wrapper.vue'

export default {
  name: 'home',
  components: {
    Header,
    Projects,
    Wrapper
  }
}
</script>

<style scoped>
.home{
  margin-top: 10vh;
}
</style>
