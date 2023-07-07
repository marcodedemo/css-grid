

<script setup>

</script>






<template>


<div class="container">

  <div class="box yellow">1</div>
  <div class="box pink">3</div>
  <div class="box purple">2</div>
  <div class="box pink">3</div>
  <div class="box blue">4</div>

  
</div>




</template>






<style scoped>


.container{

  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  grid-template-rows: 100px 300px 100px 100px;
  gap: 20px;



  width: 1000px;

}

.yellow{
  background-color: #daa521;
  grid-column: 1 / -1;
}

.purple{
  background-color: #800080;
  grid-column: 2;
  grid-row: 2 / 4;
}

.pink{
  background-color: #ee82ee;
}

.blue{
  background-color: #aed8e6;
  grid-column: 1 / -1;
}



</style>
