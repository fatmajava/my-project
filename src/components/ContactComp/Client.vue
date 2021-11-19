<template>


<b-container>
        <!-- div class="row" -->
        <b-row class="text-center">
          <div class="data-client">
          <h2>Our Client Are</h2>


          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi consequuntur, praesentium sint totam fugiat, quo perspiciatis iusto vel excepturi culpa minus cupiditate officia quam error eligendi necessitatibus expedita voluptatem nemo.</p>
          </div>
          
            <!-- div class="col" -->
            <b-col col lg="2 m-5" md="4" sm="12" > <img src="@/assets/img/stephenson_web_design.svg"></b-col>
            <b-col col lg="2 m-5" md="4" sm="12"><img src="@/assets/img/john_doe_design.svg"></b-col>
            <b-col col lg="2 m-5" md="4" sm="12"><img src="@/assets/img/john_stephenson.svg"></b-col>
             <b-col col lg="2 m-5" md="4" sm="12"><img src="@/assets/img/stephenson_william.svg"></b-col>
        </b-row>
    </b-container>

</template>
<style scoped>
.data-client {
  padding: 3%;
  
}
.data-client p {
  margin-left: 5%;
  margin-right: 5%;
}
</style>
<script>
export default {
    name : "Client"
}
</script>
