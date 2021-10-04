<template>
    <div>
        <div class="flex-view flex-direction-col custom-broject-container">
          <div><p class="custom-project-first-heading font-family: 'Raleway'; ">Demo our Eveloution Plan</p></div>
           <div class="flex-view flex-directon-row justify-content-b" style="
    align-items: center;">
               <div><p class="integration-text">Learn how other companies have benefitted from our evolution plan.</p></div>
               <div style="margin-top: -54px;"><button class="left-button hvr-sweep-to-right">Learn More</button></div>

           </div>
        </div>

    </div>
</template>




<script>
export default {
    name:"demoevloution"
   
}
</script>
<style >

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
       width: 1069px !important;
    border: 2px solid #f6f2f2 !important;
    margin-left: 8rem !important;
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
    margin-top: 44px;
    

}
.integration-text{
  margin-left: 7rem;
    margin-top: 0px;
    font-size: 13px;
    color: #8080809c;
    font-family: 'Raleway';
}
.left-button{
        border: 1.5px solid #00B0C2;
    border-radius: 4px;
    box-shadow: 0 3px 15px 0px #00b0c24d !important;
    height: 29px;
    width: 115px;
    color: #00B0C2;
    background-color: transparent;
    font-family: 'Raleway';
    margin-right: 5rem;
    font-size: 12px;
    margin-top: 11px;
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
@media only screen and (max-width: 767px) {
  

  .custom-broject-container {
    width: 350px !important;
    border: 2px solid #f6f2f2 !important;
    margin-left: 0rem !important;
    margin-top: 30px !important;
    height: 137px !important;
    border-radius: 5px !important;
  }
  .custom-project-first-heading {
     font-size: 23px !important;
    font-weight: bold !important;
    margin-left: 1rem !important;
    margin-bottom: 0px;
    font-family: 'Raleway' !important;
    margin-top: 19px !important;
}
.integration-text {
    margin-left: 1rem !important;
    margin-top: 0px !important;
    font-size: 15px !important;
    color: #8080809c !important;
    font-family: 'Raleway' !important;
    width: 209px !important;
}
.left-button {
    border: 1.5px solid #00B0C2;
    border-radius: 4px;
    box-shadow: 0 3px 15px 0px #00b0c24d !important;
    height: 29px;
    width: 94px !important;
    color: #00B0C2;
    background-color: transparent;
    font-family: 'Raleway';
    margin-right: 1rem !important;
    font-size: 12px;
    margin-top: 34px !important;
}
  }
  @media only screen and (max-width: 1024px) {
    

     .custom-broject-container {
    width: 704px !important;
    border: 2px solid #f6f2f2;
    margin-left: 1rem !important;
    margin-top: 30px !important;
    height: 137px !important;
    border-radius: 5px !important;
}
.custom-project-first-heading {
    font-size: 24px !important;
    font-weight: bold !important;
    margin-left: 2rem !important;
    margin-bottom: 13px !important;
    font-family: 'Raleway'!important;
    margin-top: 44px !important;
}
.integration-text {
    margin-left: 2rem !important;
    margin-top: 0px !important;
    font-size: 17px !important;
    color: #8080809c !important;
    font-family: 'Raleway' !important;
}

  }




















































  /* grow shaddow on img ............*/
  /* .grow-shadow img {
    -webkit-transition: all .2s ease-in-out;
            transition: all .2s ease-in-out;
  }
  .grow-shadow img .ticket:hover {
    -webkit-transform: scale(1.2);
    -ms-transform: scale(1.2);
        transform: scale(1.2);
    box-shadow: 10px 15px 7px lightblue;
  } */
  /* .hvr-grow-shadow {
    display: inline-block;
    vertical-align: middle;
    -webkit-transform: perspective(1px) translateZ(0);
    transform: perspective(1px) translateZ(0);
    box-shadow: 0 0 1px rgba(0, 0, 0, 0);
    -webkit-transition-duration: 0.3s;
    transition-duration: 0.3s;
    -webkit-transition-property: box-shadow, transform;
    transition-property: box-shadow, transform;
  }
  .hvr-grow-shadow:hover, .hvr-grow-shadow:focus, .hvr-grow-shadow:active {
    box-shadow: 0 10px 10px -10px rgba(0, 0, 0, 0.5);
    -webkit-transform: scale(1.1);
    transform: scale(1.1);
  } */
  </style>