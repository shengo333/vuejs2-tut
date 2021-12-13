<template>
  <div>
    <h1>{{title}}</h1>
    <ninjas></ninjas>
  </div>
</template>

<script>

import ninjas from './assets/NetNinjas.vue'


export default {
    components:{
        'ninjas': ninjas
    },
  data(){
    return{
      title: 'Ninja app'
    }
  }
}
</script>

<style>

</style>
