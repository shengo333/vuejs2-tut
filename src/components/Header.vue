<template>
  <header>
      <h1 @click="changetitle">{{title}}</h1>
  </header>
</template>

<script>

export default {
    props:{
        title: {
            type: String
        }
    },

    methods: {
        changetitle (){
          this.$emit('changeTitle', 'vue wizards')

        } 
    }
}
</script>

<style scoped>

header{
    background: lightgreen;
    padding: 10px;
}
h1{
    color: #222;
    text-align: center;
}

</style>