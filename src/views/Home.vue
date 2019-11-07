<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script lang='ts'>
// @ is an alias to /src
import { createComponent } from '@vue/composition-api'
import HelloWorld from '@/components/HelloWorld.vue'

export default createComponent({
  name: 'home',
  components: {
    HelloWorld
  },
  setup () {
    console.log('Composition API loaded')
  }
})
</script>
