<template>
  <div>
    <h1>{{ title }}</h1>
    <dota></dota>
  </div>
</template>

<script>
import Dota from './Dota.vue'

export default {
  components:{
    'dota': Dota
  },
  data () {
    return {
      title:'Your first Vue file, wooo!'
    }
  }
}
</script>
<style>

</style>
