<template>
  <div class="home">    
    <Androy greeting="I am testing out vue js once again"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Androy from '@/components/Androy.vue'

export default {
  name: 'Home',
  components: {   
    Androy
  }
}
</script>
