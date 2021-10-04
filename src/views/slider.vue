
<template>
  <div>
   <div class="slider-responsive">
      <VueSlickCarousel :arrows="false" :dots="true">
      <div style="width:700px">

       <div class="expo-container">
                <!-- <div><img class="explore-icon" src="../assets/logo_creation_white.svg" alt=""></div> -->
               <div class="internal-text">
                    <div><p class="ticket-booth-heading">Workflow Automation</p></div>
                <p class="explore-content">
                    Efficiency means everything to a growing business. Automate your workflow to open up your team’s day-to-day and increase your client bandwidth.
                </p>
                <div><button class="explore-button">Learn More</button></div>

               </div>
            </div>

      </div>
     <div style="width:700px">

       <div class="expo-container">
                <!-- <div><img class="explore-icon" src="../assets/logo_creation_white.svg" alt=""></div> -->
               <div class="internal-text">
                    <div><p class="ticket-booth-heading">Workflow Automation</p></div>
                <p class="explore-content">
                    Efficiency means everything to a growing business. Automate your workflow to open up your team’s day-to-day and increase your client bandwidth.
                </p>
                <div><button class="explore-button">Learn More</button></div>

               </div>
            </div>

      </div>
       <div style="width:700px">

       <div class="expo-container">
                <!-- <div><img class="explore-icon" src="../assets/logo_creation_white.svg" alt=""></div> -->
               <div class="internal-text">
                    <div><p class="ticket-booth-heading">Workflow Automation</p></div>
                <p class="explore-content">
                    Efficiency means everything to a growing business. Automate your workflow to open up your team’s day-to-day and increase your client bandwidth.
                </p>
                <div><button class="explore-button">Learn More</button></div>

               </div>
            </div>

      </div>
      <div style="width:700px">

       <div class="expo-container">
                <!-- <div><img class="explore-icon" src="../assets/logo_creation_white.svg" alt=""></div> -->
               <div class="internal-text">
                    <div><p class="ticket-booth-heading">Workflow Automation</p></div>
                <p class="explore-content">
                    Efficiency means everything to a growing business. Automate your workflow to open up your team’s day-to-day and increase your client bandwidth.
                </p>
                <div><button class="explore-button">Learn More</button></div>

               </div>
            </div>

      </div>
    </VueSlickCarousel>
 
      <div class="flex-view flex-direction-row justify-content-c team-row">
          <div class="flex-view flex-direction-row concept-icon ">
            <div class="icon ">  <img style="width:40px"  src="../assets/team1.png" alt /></div>
              <p class="content">Concept production</p>
              
              </div>
               
               <div class="flex-view flex-direction-row">
              <div class="icon" ><img style="width:40px" src="../assets/carban3.png" alt /></div>
              <p class="content">Development</p>
              
              </div>

              <div class="flex-view flex-direction-row">
              <div class="icon" ><img style="width:40px" src="../assets/team3.png" alt /></div>
              <p class="content">Data Management</p>
              
              </div>

              <div class="flex-view flex-direction-row">
            <div class="icon" ><img style="width:40px" src="../assets/carban4.png" alt /></div>
              <p class="content">Marketing</p>
              
              </div>

              <div class="flex-view flex-direction-row">
            <div class="icon" ><img style="width:40px" src="../assets/integrations-team.png" alt /></div>
              <p class="content">Integration</p>
              
              </div>
     

      </div>
     
   </div>

  </div>
</template>
 
<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
</script> 
<style scoped>
.icon:hover + .content{
    display: block;
        transition: all 0.4s ease-in-out;
            /* border: 1px solid #ffc10778;
    border-radius: 4px;
    background-color: #ffc10726;
  */
}
.icon:hover + .concept-icon{
    border: 1px solid #ffc10778;
    border-radius: 4px;
    background-color: #ffc10726;
}

.content{
     width: 70px;
    display: none;
    /* display: none; */
    font-size: 12px;
    /* text-align: left; */
    font-weight: bold;
    text-align: start;
    margin-left: -9px;
}
.icon{
    /* margin-right: 29px;
    margin-left: 10px;
    width: 42px;
    padding-top: 11px; */
        /* margin-right: 29px; */
    margin-left: 10px;
    width: 42px;
    margin-right: 20px;
}
.team-row{
            border: 1px solid;
    background-color: #f0f2f5;
    margin: 0px auto;
    width: 45%;
    position: absolute;
    right: 27%;
    bottom: 16%;
    height: 71px;
    border-radius: 4px;
    border: none;
    align-items: center;
}
.expo-container{
     background-size: 1057px;
    background-repeat: no-repeat;
    /* background-image: url(/img/feat_integ.fa7f778a.jpeg); */
    background-image: url(/img/feat.fa7f778a.jpeg);
    width: 1057px;
    height: 399px;
    margin-left: 87px;
    border-radius: 4px;
    MARGIN: 0px auto;
    margin-top: 31px;
  }
   .explore-content{
       width: 311px;
    font-size: 15px;
    margin-top: 9px;
    color: #fff;
    line-height: 22px;
    font-family: 'Raleway';

  }
   .explore-button{
        width: 102px;
    height: 32px;
    font-size: 14px;
    color: #ffff;
    border: none;
    background-color: transparent;
    border: 1px solid;
    font-size: 11px;
    text-align: center;
    border-radius: 3px;
    margin: 0px;
  }
  .internal-text{
    padding: 76px 53px;
    margin-left: 62%;
  }
  .explore-button:hover{
      background-color: white;
    color: #17a2b8;;
  }

  @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,300;1,100&display=swap');
.flex-direction-col {
    flex-direction: column;
  }
  .flex-direction-col-row {
    flex-direction: column;
  }
  .flex-direction-row-col {
    flex-direction: row;
  }
  .flex-view {
    display: flex;
  }
  .flex-direction-row {
    flex-direction: row;
  }
  .justify-content-c {
    justify-content: center;
  }
  .justify-content-b {
    justify-content: space-between;
  }
  .justify-content-a {
    justify-content: space-around;
  }

   @media only screen and (max-width: 767px) {
  

  .slider-responsive{
    display: none;
  }
    
}
   @media only screen and (max-width: 1024px) {
      
      .expo-container{
        background-size: 778px !important;
    background-repeat: no-repeat;
    /* background-image: url(/img/feat_integ.fa7f778a.jpeg); */
    background-image: url(/img/feat.fa7f778a.jpeg);
    width: 716px;
    height: 399px;
    margin-left: 87px;
    border-radius: 4px;
    MARGIN: 0px auto;
    margin-top: 31px;
      }
      .explore-content[data-v-2f31520a] {
    width: 202px;
    font-size: 14px;
    margin-top: 9px;
    color: #fff;
    line-height: 21px;
    font-family: 'Raleway';
}
.team-row[data-v-2f31520a] {
    border: 1px solid;
    background-color: #f0f2f5;
    margin: 0px auto;
    width: 59%;
    position: absolute;
    right: 20%;
    bottom: 48%;
    height: 71px;
    border-radius: 4px;
    border: none;
    align-items: center;
}
   }


</style>