<template>
  <div id="app">
    <Container>
      <template #header>
        header
      </template>
      <template #main>
        <Test/>
      </template>
      <template #footer>
        footer
      </template>
    </Container>
  </div>
</template>

<script>
import Test from './components/test.vue'
import Container from './components/container.vue'

export default {
  name: 'App',
  components: {
    Test,
    Container
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
