<template>
  <div class="home">
    <Personaje/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Personaje from '@/components/Personaje.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Personaje

  }
}
</script>
