<template>
  <v-app>
    <v-main>
      <HelloWorld msg="Welcome to Your Vue.js App" />
    </v-main>
  </v-app>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
