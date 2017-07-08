<template>
    <ul>
        <li v-for="heroes in dota">{{ heroes }}</li>
    </ul>

</template>

<script>
export default {
  data () {
    return {
      dota: ['Magina','Winrunner']
    }
  }
}
</script>

<style>

</style>

