<template>
  <header>
      <h1 @click="changetitle">{{title}}</h1>
  </header>
</template>

<script>
export default {
    data(){
        return{
            title: 'Vue Ninjas'
        }
    },
    props:{
        title: {
            type: String
        }
    },

    methods: {
        changetitle (){
            this.title = "vue wizards"
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