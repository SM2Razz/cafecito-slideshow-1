
<template>
  <div id="app">
    <header>
      <img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />

      <h1>I am the APP!</h1>
      <div class="wrapper">
        <HelloWorld msg="Hi Hi hello!" />
      </div>
    </header>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
  }
}
</script>

<style scoped>

</style>
