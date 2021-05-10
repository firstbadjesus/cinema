<template>
   <div class="cinema">
      <div class="cinema-block">
         <div class="monitor">
            Screen
         </div>
         <div class="places">
            <div class="place">1</div>
            <div class="place">2</div>
            <div class="place">3</div>
            <div class="place">4</div>
            <div class="place">5</div>
            <div class="place">6</div>
            <div class="place">7</div>
            <div class="place">8</div>
            <div class="place">910</div>

            <!-- <div class="place">0</div> -->
         </div>
      </div>
   </div>
</template>

<script>

</script>

<style>
.cinema {
   color: green;
   padding: 39px;
   background-color: red;
   
}
.cinema-block {
   margin: auto;
   width: 600px;
}
.monitor{
   background-color: white;
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
   border-radius: 15px;
}

.place:hover{
   background-color:rgb(17, 82, 17);
}
.place:active{
   background-color: rgb(187, 187, 4);
}
</style>