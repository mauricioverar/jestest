<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Registrar/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Registrar from '@/components/Registrar.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Registrar
  }
}
</script>
