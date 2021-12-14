<template>
  <div>
    <Header :title="title"/>
    <Ninjas :ninjas="ninjas" />
    <Footer :title="title"/>
    
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Footer from './components/footer.vue'
import Ninjas from './components/Ninjas.vue'


export default {
    components:{
         Header,
         Footer,
         Ninjas,
    },
  data(){
    return{
        ninjas: [
          {name: 'Ryu', speciality: 'Vue Components', show: false},
          {name: 'Crystal', speciality: 'HTML Wizardry', show: false},
          {name: 'Hitoshi', speciality: 'Click Events', show: false},
          {name: 'Tango', speciality: 'Conditionals', show: false},
          {name: 'Kami', speciality: 'Webpack', show: false},
          {name: 'Yoshi', speciality: 'Data Diggin', show: false}
        ],
        title: "Irakli"
    }
  }
}
</script>

<style scoped>
h1{
  color: purple
}


</style>
