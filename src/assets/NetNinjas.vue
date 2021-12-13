<template>
    <ul>
        <li v-for="beka in bekas" :key="beka">{{beka}}</li>
    </ul>
</template>

<script>

export default {

  data(){
    return{
      bekas:['Yoshi', 'Mario', 'Rauy']
    }
  }
}
</script>

<style>

</style>
