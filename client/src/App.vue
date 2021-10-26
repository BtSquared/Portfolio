<template>
  <div class="flexCon">
    <NavBar />
    <div class="columnCon">
      <AboutMe />
      <Projects />
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import AboutMe from './components/AboutMe.vue'
import Projects from './components/Projects.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    AboutMe,
    Projects
  }
}
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(237, 237, 237);
  margin-top: 60px;
}
.flexCon {
  display: flex;
  background-image: url('https://images.pexels.com/photos/3472764/pexels-photo-3472764.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260');
  background-attachment: fixed;
  background-size: cover;
  width: 100vw;
  height: 100vh;
  font-size: 24px;
  color: rgb(237, 237, 237);
}
.columnCon {
  display: flex;
  flex-direction: column;
}
</style>
