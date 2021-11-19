<template>
  <div>
    <Client/>
    <Footer/>
  </div>
</template>
<script>
import Client from '@/components/ContactComp/Client.vue'
import Footer from '@/components/ContactComp/Footer.vue'
export default {
    name : "Contacts",
    components:{
       Client ,
       Footer,
        
    }
}
</script>

