<template>
  <div>
    <Header />
    <Ninjas />
    <Footer />
    
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

    }
  }
}
</script>

<style scoped>
h1{
  color: purple
}


</style>
