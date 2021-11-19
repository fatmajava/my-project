<template>
<div class="back">
<div class="container">  
    <p class="details"> @All Right Reserved</p>
    <div>
      <b-icon icon="facebook" class="mx-2" ></b-icon>
     <b-icon icon="twitter" class="mx-2" ></b-icon>
    <b-icon icon="google" class="mx-2" ></b-icon>
    </div>
  </div>
  </div>
</template>
<style scoped>
.container{
    width: 80%;
    display: flex;
    justify-content: space-between;
}

.back {
    background-color: var(--main-color);
    color: var(--white);
    padding: 6%;
}


</style>

<script>
export default {
    name : "Footer"
}
</script>
