<template>
   <div class="cinema">
      <div class="cinema-block">
         <div class="monitor">
            Screen
         </div>
         <div class="places">
            <div @click="orderPlace(1,1)" class="place">1</div>
            <div @click="orderPlace(1,2)" class="place">2</div>
            <div @click="orderPlace(1,3)" class="place">3</div>
            <div @click="orderPlace(2,1)" class="place">4</div>
            <div @click="orderPlace(2,2)" class="place">5</div>
            <div @click="orderPlace(2,3)" class="place">6</div>
            <div @click="orderPlace(3,1)" class="place">7</div>
            <div @click="orderPlace(3,2)" class="place">8</div>
            <div @click="orderPlace(3,3)" class="place">9</div>
         </div>
      </div>
   </div>
</template>

<script>
export default {
   methods: {
      orderPlace(row, column) {
         console.log('asihdbasuyfbuasyf', row, column)
      }
   }
}
</script>

<style>
.cinema {
   color: white;
   padding: 39px;
   background-color: red;
   
}
.cinema-block {
   margin: auto;
   width: 600px;
}
.monitor{
   background-color:gray;
   padding: 15px;
   text-transform: uppercase;
   margin-bottom: 20px;
   
}
.places {
   display: grid;
   grid-template-columns: repeat(3, 1fr);
   
}
.place{
   width: 170px;
   height: 170px;
   background-color: rgb(13, 194, 13);
   display: flex;
   justify-content: center;
   align-items: center;
   font-size: 30px;
   margin: 15px;
}

.place:hover{
   background-color:rgb(17, 82, 17);
}
.place:active{
   background-color: rgb(187, 187, 4);
}
</style>