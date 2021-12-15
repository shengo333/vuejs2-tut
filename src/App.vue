<template>
  
  <formHelper>
    <template v-slot:title> <h3> {{title}}</h3> </template>
    
    <template v-slot:form-header>
      <h3>This is the title of the form </h3>
      <p>information about the slot</p>
    </template>

    <template v-slot:form-fields>
      <input type="text" placeholder="name" required>
      <input type="password" placeholder="password" required>
    </template>

    
    <template v-slot:form-controls>
      <button @click="handleSubmit">Submit</button>
    </template>

  </formHelper>
</template>

<script>

import formHelper from './components/formHelper.vue'



export default {
    components:{
         formHelper,
        
    },
  data(){
    return{
      title: 'i am dynamic slot title'
    }
  },
  methods:{

  }
}
</script>

<style scoped>

h3{
  color: red
}

</style>
