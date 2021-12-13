<template>
  <div>
    <h1>{{title}}</h1>
    <p>{{greeting()}}</p>
  </div>
</template>

<script>

export default {
  data(){
    return{
      title: 'this is vue CLI'
    }
  },
  methods:{
    greeting(){
      return 'hay cli boy'
      console.log('this is it')
    }
  }
}
</script>

<style>

</style>
