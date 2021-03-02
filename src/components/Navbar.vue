<template>
  <div id="navbar">
    <nav>
      <h1 class="animate__animated animate__bounceIn">Hi, I'm an animated title</h1>
      <font-awesome-icon icon="spinner" />
      <button @click="click" class="btn btn-primary">Click Me</button>
      <router-link to="/about">About</router-link>
      <router-link to="/">Home Page</router-link>
     </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  methods: {
    click () {
      this.$alert('Hello Vue Simple Alert.')
    }
  }
}
</script>

<style scoped>

</style>
