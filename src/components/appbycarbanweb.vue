<template>
    <div class="flex-view flex-direction-col justify-content-b">
        <div class="flex-view flex-direction-row" style=" align-items: center;     padding: 35px 0px 0px;">
            <div><img class="carbotext-svg" src="../assets/carbotext.svg" alt=""></div>
            <div><p class="app-text">Apps by CarbonWeb</p></div>
            <!-- <div class="flex-view flex-direction-row">
              <div>  <i class=" circule fa fa-circle" aria-hidden="true"></i></div>
                <div><hr class="hr"></div>
            </div> -->
            <div class="flex-view flex-direction-row">
        <div>
          <i class="circule fa fa-circle" aria-hidden="true"></i>
        </div>
        <div class="hr"></div>          
      </div>

        </div>
        <div><p class="our-team-text">Our team developed these applications to fill the gaps of what current programs offer. These apps will help streamline your workflow and open up new possibilities for your team</p></div>
        <div class="flex-view flex-direction-row justify-content-c app-responsoive-img tab-responsive">
            <div><img class="ticket hvr-shadow" src="../assets/ticket.png" alt=""></div>
            <div class="flex-view flex-direction-col explore-contianer">
                <div><img class="explore-icon" src="../assets/boothwhite.svg" alt=""></div>
                <div><p class="ticket-booth-heading">Ticketbooth</p></div>
                <p class="explore-content">Transform your monday.com client overview board into an interactive ticketing view where you can support and manage your clients.</p>
                <div><button class="explore-button">Explore <i class="fa fa-arrow-right" aria-hidden="true"></i> </button></div>

            </div>
            <div class="flex-view flex-direction-col fair-phone-container">
                <div><img class="fair-img" src="../assets/fairphone.jpg" alt=""></div>
                <div><p class="fair-img-heading">PhoneBurner monday.com App</p></div>
                <div><p class="fair-content">Access PhoneBurner’s inbound and outbound services within monday.com to empower your sales team to drive more appointments and track sales.s</p></div>
                <div style="text-align: end;">
                    <button class="fair-explore-button">Explore <i class="fa fa-arrow-right" aria-hidden="true"></i>
                    </button>
                </div>

            </div>
        </div>
        <div class="flex-view flex-direction-col custom-broject-container">
          <div><p class="custom-project-first-heading font-family: 'Raleway'; ">Have a custom project in mind?</p></div>
           <div class="flex-view flex-directon-row justify-content-b" style="
    align-items: center;">
               <div><p class="integration-text">Learn more about how we develop custom integrations.</p></div>
               <div style="margin-top: -54px;"><button class="left-button hvr-sweep-to-right">Learn More</button></div>

           </div>
        </div>
         <div class="flex-view flex-direction-col custom-broject-container">
          <div><p class="custom-project-first-heading ">Have a custom project in mind?</p></div>
           <div class="flex-view flex-directon-row justify-content-b" style="
    align-items: center;">
               <div><p class="integration-text">Learn more about how we develop custom integrations.</p></div>
               <div style="margin-top: -54px;"><button class="left-button hvr-sweep-to-right ">Learn More</button></div>

           </div>
        </div>
    </div>
</template>




<script>
export default {
    name:"appbycarbanweb"
   
}
</script>
<style scoped>

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
  .carbotext-svg{
     width: 69px;
    padding-left: 124px;
  }
  .app-text{
        font-weight: bold;
    margin-left: 27px;
    font-size: 21px;
    font-family: 'Raleway';
    /* font-weight: bold; */
    font-style: normal;
    font-weight: 600;

  }
  .circule{
    color: #B7BFDD !important;
    font-size: 14px !important;
    margin-left: 40px !important;
  }
  .hr{
  height: 1px;
    background-image: linear-gradient(to right, #b7bfdd, 75%, rgba(183, 191, 221, 0));
    margin-top: 10px;
    width: 495px;
  }
  .our-team-text{
   font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 32px;
    color: #9093A2;
    margin-top: 17px;
    margin-bottom: 10px;
    width: 887px;
    margin-left: 8rem;
    font-size: 12px;
    font-family: 'Raleway';

  }
  .ticket{
   margin-top: 37px;
    width: 829px !important;
    position: relative;
    border-radius: 4px;
    height: 308px;
    
  }
  /* .ticket:hover{

  } */
  .explore-contianer{
 position: absolute;
    right: 33%;
    top: 242%;
    width: 276px;
    font-size: 0px;
  }
  .explore-icon{
   height: 40px;
    width: 40px;
    margin-right: 10px;
    border-radius: 4px;
    background-color: rgba(255, 255, 255, 0.25);
    padding: 5px;
  }
  .ticket-booth-heading{
        text-overflow: ellipsis;
    font-size: 17px;
    color: #fff;
    margin-top: 11px;
    font-family: 'Raleway';
    font-weight: bold;
  }
  .explore-content{
  width: 237px;
    font-size: 15px;
    margin-top: 9px;
    color: #fff;
    line-height: 22px;
    font-family: 'Raleway';

  }
  .explore-button{
      /* width: 165px; */
    height: 37px;
    font-size: 21px;
    color: #ffff;
    border: none;
    background-color: transparent;
    text-align: right;
    margin-left: 8rem;
    /* /* margin-top: 1rem; */
  }
  
  .fair-phone-container{
         border: 2px solid #80808038;
    width: 265px;
    height: 300px;
    margin-top: 37px;
    margin-left: 16px;
    border-radius: 5px;
  }
  .fair-img{
      width: 40px;
    border-radius: 18px;
    padding: 14px;
  }
  .fair-img-heading{
   font-size: 15px;
    color: black;
    margin-left: 12px;
    margin: 0px auto;
    margin-left: 12px;
    font-weight: bold;
    font-family: 'Raleway';

  }
  .fair-content{
   font-size: 14px;
    line-height: 23px;
    padding: 10px;
    color: gray;
    /* font-size: -webkit-xxx-large; */
    margin: 0px auto;
    font-family: 'Raleway';
  }
.fair-explore-button{
 width: 110px;
    font-size: 18px;
    margin-top: 11px;
    border: none;
    background-color: transparent;
}
.shadow-green{
  -webkit-box-shadow: 0px 25px 25px -15px #00b0c2;
  box-shadow: 0px 25px 25px -15px #00b0c2;
  background: #00B0C2 !important;
  border: 0px !important;


}
.fair-phone-container:hover:hover{

  -webkit-box-shadow: 0px 25px 25px -15px #00b0c2;
  box-shadow: 0px 25px 25px -15px #00b0c2;
  background: #00B0C2 !important;
  border: 0px !important;
  color: white;

}

.fair-phone-container:hover .fair-img-heading{
  color: white;
}
.fair-phone-container:hover .fair-content{
  color: white;
}
.fair-phone-container:hover .fair-explore-button{
  color: white;
}
.custom-broject-container{
  width: 1114px !important;
    border: 2px solid #f6f2f2 !important;
    margin-left: 7rem !important;
    margin-top: 30px !important;
    height: 137px !important;
    border-radius: 5px !important;
}
.custom-project-first-heading{
     font-size: 22px;
    font-weight: bold;
    margin-left: 7rem;
    margin-bottom: 13px;
    font-family: 'Raleway';
    margin-top: 37px;
    

}
.integration-text{
    margin-left: 7rem;
    margin-top: 0px;
    font-size: 16px;
    color: #8080809c;
    font-family: 'Raleway';
}
.left-button{
     border: 1.5px solid #00B0C2;
    border-radius: 4px;
    box-shadow: 0 3px 15px 0px #00b0c24d !important;
    height: 33px;
    width: 132px;
    color: #00B0C2;
    background-color: transparent;
    font-family: 'Raleway';
    margin-right: 5rem;
}
.custom-broject-container:hover{
  -webkit-box-shadow: 0px 25px 25px -15px #00b0c2;
  box-shadow: 0px 25px 25px -15px #00b0c2;
  background: #00B0C2 !important;
  border: 0px !important;
  color: white;
  transition: all 0.35s ease-Out;
  

}
.custom-broject-container:hover .left-button{
  background-color: #fff;
}
.custom-broject-container:hover .integration-text{
  color: #fff;
}

.hvr-sweep-to-right {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
  position: relative;
  -webkit-transition-property: color;
  transition-property: color;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
}
.hvr-sweep-to-right:before {
  content: "";
  position: absolute;
  z-index: -1;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: #00b0c2;
  -webkit-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transform-origin: 0 50%;
  transform-origin: 0 50%;
  -webkit-transition-property: transform;
  transition-property: transform;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}
.hvr-sweep-to-right:hover, .hvr-sweep-to-right:focus, .hvr-sweep-to-right:active {
  color: white;
}
.hvr-sweep-to-right:hover:before, .hvr-sweep-to-right:focus:before, .hvr-sweep-to-right:active:before {
  -webkit-transform: scaleX(1);
  transform: scaleX(1);
}

.hvr-shadow {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-property: box-shadow;
  transition-property: box-shadow;
}
.hvr-shadow:hover, .hvr-shadow:focus, .hvr-shadow:active {
  box-shadow: 0px 25px 25px -15px #69caf7;
}


 @media only screen and (min-width: 768px) and (max-width:1024px) {
 
 .carbotext-svg[data-v-a5fdcfde] {
    width: 69px;
    padding-left: 41px;
}
.app-text[data-v-a5fdcfde] {
    font-weight: bold;
    margin-left: 15px;
    font-size: 23px;
    font-family: 'Raleway';
    /* font-weight: bold; */
    font-style: normal;
    width: 218px;
    font-weight: 600;
}
.hr[data-v-a5fdcfde] {
    height: 1px;
    background-image: linear-gradient(to right, #b7bfdd, 75%, rgba(183, 191, 221, 0));
    margin-top: 10px;
    width: 319px;
}
.our-team-text[data-v-a5fdcfde] {
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 32px;
    color: #9093A2;
    margin-top: 17px;
    margin-bottom: 10px;
    width: 685px;
    margin-left: 3rem;
    font-size: 18px;
    font-family: 'Raleway';
}
.ticket{
  display: none;
}
 
 .explore-contianer[data-v-a5fdcfde] {
    width: 300px;
    font-size: 0px;
    height: 287px;
    margin-top: 36px;
    border: 2px solid #9e9e9e63;
    border-radius: 4px;
    position: revert;
    padding: 15px;
}
.fair-phone-container[data-v-a5fdcfde] {
    border: 2px solid #80808038;
    width: 331px;
    height: 315px;
    margin-top: 37px;
    margin-left: 16px;
    border-radius: 5px;
}
.explore-icon[data-v-a5fdcfde] {
    height: 40px;
    width: 40px;
    margin-right: 10px;
    border-radius: 4px;
    background-color: rgba(255, 255, 255, 0.25);
    padding: 5px;
    background-color: #9e9e9e6b;
}
.ticket-booth-heading[data-v-a5fdcfde] {
    text-overflow: ellipsis;
    font-size: 17px;
    color: #fff;
    margin-top: 11px;
    font-family: 'Raleway';
    font-weight: bold;
    color: black;
    font-weight: bold;
}
.explore-content[data-v-a5fdcfde] {
    width: 237px;
    font-size: 15px;
    margin-top: 9px;
    color: black;
    line-height: 22px;
    font-family: 'Raleway';
}
.explore-button[data-v-a5fdcfde] {
       width: 167px;
    height: 37px;
    font-size: 21px;
    color: black;
    border: none;
    background-color: transparent;
    text-align: right;
    margin-left: 8rem;
    margin-top: 30px;
}
.fair-explore-button[data-v-a5fdcfde] {
    font-size: 22px;
    border: none;
    background-color: transparent;
    margin-top: 61px;
    padding-right: 21px;
}
.custom-broject-container[data-v-a5fdcfde] {
    width: 689px !important;
    border: 2px solid #f6f2f2 !important;
    margin-left: 2rem !important;
    margin-top: 30px !important;
    height: 137px !important;
    border-radius: 5px !important;
}
.recommended-svg[data-v-7226820a] {
    width: 75px;
    margin-left: 1rem;
}
 
 }






@media only screen and (max-width: 767px) {
  .carbotext-svg {
   width: 95px !important;
    padding-left: 0px !important;
}
.app-text {
    font-weight: bold;
    margin-left: 14px;
    font-size: 26px;
    font-family: 'Raleway';
    /* font-weight: bold; */
    font-style: normal;
    font-weight: 600;
}
.hr {
    height: 1px;
    background-image: linear-gradient(to right, #1a1b1f, 75%, rgba(183, 191, 221, 0));
    margin-top: 6px;
    width: 625px;
    display: none ;
}
.circule{
  display: none;
}
.our-team-text {
   font-style: normal;
    font-weight: normal;
    font-size: 16px;
    line-height: 27px;
    color: #9093A2;
    margin-top: 17px;
    margin-bottom: 10px;
    width: 362px;
    margin-left: 0rem;
    font-size: 17px;
    font-family: 'Raleway';
}
.app-responsoive-img{
  display: flex;
  flex-direction: column;
}
.ticket {
  margin-top: 37px;
    width: 1054px !important;
    position: relative;
    border-radius: 4px;
    height: 525px !important;
    margin-left: 6rem;
    display: none;
}
.explore-contianer {
  position: inherit;
    right: -184%;
    top: 372%;
    font-size: 0px;
    border: 2px solid #9e9e9e63;
    border-radius: 6px;
    height: 354px;
    width: 350px;
}
.fair-phone-container {
         border: 2px solid #80808038;
    height: 345px;
    width: 353px;
    margin-top: 37px;
    margin-left: 0px;
    border-radius: 5px;
}
.explore-icon {
   height: 65px;
    width: 53px;
    border-radius: 4px;
    background-color: rgba(255, 255, 255, 0.25);
    padding: 13px;
        background: linear-gradient(
45deg, #9e9e9e, transparent);
}
.ticket-booth-heading {
   text-overflow: ellipsis;
    font-size: 24px;
    color: #fff;
    font-family: 'Raleway';
    font-weight: bold;
    margin-top: 45px;
    padding-left: 10px;
    color: black;
    margin-bottom: 0px;
}
.explore-content {
   width: 333px;
    font-size: 16px;
    color: #fff;
    line-height: 25px;
    font-family: 'Raleway';
    color: black;
    padding-left: 15px;
}
.explore-button {
    width: 100%;
    height: 37px;
    font-size: 30px;
    color: #ffff;
    border: none;
    background-color: transparent;
    margin-left: 0rem;
    margin-top: 21px;
    font-size: 28px;
    color: black;
}
.fair-img {
       width: 68px;
    border-radius: 11px;
    padding: 8px;
}
.fair-img-heading {
   font-size: 25px;
    color: black;
    margin-left: 12px;
    margin: 0px auto;
    margin-left: 12px;
    font-weight: bold;
    font-family: 'Raleway';
}
.fair-content {
 margin-top: 37px;
    margin-left: 0px;
    border-radius: 5px;
}
.fair-explore-button {
    width: 100%;
    font-size: 25px;
    margin-top: 22px;
    border: none;
    background-color: transparent;
    text-align: end;
}
.custom-broject-container {
   width: 357px !important;
    border: 2px solid #607d8b8f !important;
    margin-left: 0rem !important;
    margin-top: 30px !important;
    height: 129px !important;
    border-radius: 5px !important;
}
.custom-project-first-heading {
    font-size: 23px;
    font-weight: bold;
    margin-left: 1rem;
    margin-bottom: -40px;
    font-family: 'Raleway';
    margin-top: 6px;
    width: 100%;
    max-width: 247px;
}
.integration-text {
        margin-left: 1rem;
    margin-top: 48px;
    font-size: 16px;
    color: #5c2d2d;
    font-family: 'Raleway';
    width: 233px;
}
.left-button[data-v-a5fdcfde] {
    border: 1.5px solid #00B0C2;
    border-radius: 4px;
     border: 2px solid #9e9e9e54!important;
    height: 33px;
    width: 91px;
    color: #00B0C2;
    background-color: transparent;
    font-family: 'Raleway';
    margin-right: 7px;
    margin-top: 35px;
}
}

  
  </style>