<template>
  <div id="app">
    <topPage/>
    <aboutMe/>
    <midlePart/>
    <formContact/>
  </div>
</template>

<script>
import topPage from './components/topPage.vue'
import aboutMe from './components/aboutMe.vue'
import midlePart from './components/midlePart.vue'
import formContact from './components/formContact.vue'

export default {
  name: 'app',
  components: {
    topPage,
    aboutMe,
    midlePart,
    formContact
  }
}
</script>

<style>
#app {
  height: 100%;
  margin-top: 0px;
  background-color: #efe7e5;
  color: black;
}
</style>  
