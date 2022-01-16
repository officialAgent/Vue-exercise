<template>
  <div class="font-sans bg-gray-900 text-white"  id="app">

    <Header />
    <MainContent/>
    <ShowTeacher/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import MainContent from "@/components/MainContent";
import ShowTeacher from "@/components/ShowTeacher";

export default {
  name: 'App',
  components: {
    Header,
    MainContent,
    ShowTeacher

  }
}
</script>

<style>
/*#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
