<template>
    

<div id="scroll">
  <div class="flex-view flex-direction-col justify-content-b">
    <div class="flex-view flex-direction-row" style=" align-items: center; padding: 35px 0px 0px;">
      <div>
        <img class="carbotext-svg" src="../assets/team2.png" alt />
      </div>
      <div>
        <p class="app-text">Development</p>
      </div>
      <!-- <div class="flex-view flex-direction-row">
              <div>  <i class=" circule fa fa-circle" aria-hidden="true"></i></div>
                <div><hr class="hr"></div>
      </div>-->
      <div class="flex-view flex-direction-row">
        <div>
          <i class="circule fa fa-circle" aria-hidden="true"></i>
        </div>
        <div class="hr"></div>
      </div>
    </div>
    <div>
      <p
        class="our-team-text"
      >The identity of your company relies on strong content and branding that fits what your company is all about. Our team sheds light on your company values to help intrigue new and returning customers.</p>
    </div>
    <div class="flex-view flex-direction-row justify-content-a main-width">
      <!-- <div><img class="ticket hvr-shadow" src="../assets/ticket.png" alt=""></div> -->
      <div class="expo-container hvr-shadow">
        <div>
          <img class="explore-icon" src="../assets/Devsectionservice1_white.svg" alt />
        </div>
        <div>
          <p class="ticket-booth-heading">Brand Development</p>
        </div>
        <p
          class="explore-content"
        >Create a logo that showcases your values and improve brand recognition with a brand guide</p>
        <div>
          <button class="explore-button">
            Explore
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </button>
        </div>
      </div>
      <div class="flex-view flex-direction-col fair-phone-container new-contant">
        <div>
          <img class="fair-img" src="../assets/web_design.svg" alt />
        </div>
        <div>
          <p class="fair-img-heading">Content creation</p>
        </div>
        <div>
          <p
            class="fair-content"
          >Fill your online presence with content that retains site visitors and makes them take the next step towards becoming a customer.</p>
        </div>
        <div style="text-align: end;">
          <button class="fair-explore-button">
            Explore
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </button>
        </div>
      </div>
    </div>
    <div class="flex-view flex-direction-col fair-phone-container fair-phone-secont-box">
      <div>
        <img class="fair-img" src="../assets/web_update.svg" alt />
      </div>
      <div>
        <p class="fair-img-heading">Website Updats</p>
      </div>
      <div>
        <p
          class="fair-content"
        >Fill your online presence with content that retains site visitors and makes them take the next step towards becoming a customer.</p>
      </div>
      <div style="text-align: end;">
        <button class="fair-explore-button">
          Explore
          <i class="fa fa-arrow-right" aria-hidden="true"></i>
        </button>
      </div>
    </div>
  </div>
  </div>
</template>





<script>
export default {
  name: "development",
   data() {
      return {
      };
    },
};
</script>
 <style scoped>
@import url("https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,300;1,100&display=swap");
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
.main-width {
  width: 1224px !important;
}
.expo-container {
  /* background-size: 527px;
    background-repeat: no-repeat;
    background-position-x: -1px;
    width: 522px;
    height: 252px;
    margin-left: 87px;
    border-radius: 4px; */

  background-size: 747px;
  background-repeat: no-repeat;
  background-position-x: -1px;
  /* background-image: url(../assets/concet-img.jpeg); */
  /* background-image: url(..assets/.cone.jpeg); */
  background-image: url(../assets/feat_evolution.jpeg);
  width: 731px;
  height: 294px;
  margin-left: 87px;
  border-radius: 4px;
}

.carbotext-svg {
  width: 42px;
  padding-left: 124px;
}
.app-text {
  font-weight: bold;
  margin-left: 27px;
  font-size: 21px;
  font-family: "Raleway";
  /* font-weight: bold; */
  font-style: normal;
  font-weight: 600;
}
.circule {
  color: #b7bfdd !important;
  font-size: 14px !important;
  margin-left: 40px !important;
}
.hr {
  height: 1px;
  background-image: linear-gradient(
    to right,
    #b7bfdd,
    75%,
    rgba(183, 191, 221, 0)
  );
  margin-top: 10px;
  width: 495px;
}
.our-team-text {
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 22px;
  color: #9093a2;
  margin-top: 3px;
  margin-bottom: 10px;
  width: 819px;
  margin-left: 8rem;
  font-size: 12px;
  font-family: "Raleway";
}
.ticket {
  margin-left: 6rem;
  margin-top: 37px;
  /* width: 832px; */
  /* height: 394px; */
  position: relative;
  border-radius: 4px;
  height: 268px;
  width: 595px;
}
/* .ticket:hover{

  } */
.explore-contianer {
  position: absolute;
  right: 33%;
  top: 72%;
  width: 276px;
  font-size: 0px;
}
.explore-icon {
  width: 40px;
  margin-right: 10px;
  border-radius: 4px;
  background-color: rgba(255, 255, 255, 0.25);
  padding: 5px;
  margin-left: 60%;
  margin-top: 13px;
}
.ticket-booth-heading {
  text-overflow: ellipsis;
  font-size: 17px;
  color: #fff;
  margin-top: 11px;
  font-family: "Raleway";
  font-weight: bold;
  width: 168px;
  margin-left: 60%;
}
.explore-content {
  font-size: 15px;
  margin-top: 9px;
  line-height: 21px;
  font-family: "Raleway";
  width: 38%;
  margin-left: 60%;
}
.explore-button {
  /* width: 165px; */
  height: 37px;
  font-size: 21px;
  color: #ffff;
  border: none;
  background-color: transparent;
  text-align: right;
  margin-left: 73%;
}

.fair-phone-container {
  margin-top: 0px;
    height: 287px;
    width: 297px;
    border: 2px solid #9e9e9e5e !important;
    border-radius: 6px;

}

.fair-phone-secont-box {
  margin-left: 125px !important;
  margin-top: 16px !important;
}
.fair-img {
  width: 50px;
  padding: 6px;
}
.fair-img-heading {
  font-size: 15px;
  color: black;
  margin-left: 12px;
  margin: 0px auto;
  margin-left: 12px;
  font-weight: bold;
  font-family: "Raleway";
}
.fair-content {
  font-size: 14px;
  line-height: 23px;
  padding: 10px;
  color: gray;
  /* font-size: -webkit-xxx-large; */
  margin: 0px auto;
  font-family: "Raleway";
}
.fair-explore-button {
  width: 110px;
  font-size: 18px;
  margin-top: 11px;
  border: none;
  background-color: transparent;
}
.shadow-green {
  -webkit-box-shadow: 0px 25px 25px -15px #00b0c2;
  box-shadow: 0px 25px 25px -15px #00b0c2;
  background: #00b0c2 !important;
  border: 0px !important;
}
.fair-phone-container:hover:hover {
  -webkit-box-shadow: 0px 25px 25px -15px #00b0c2;
  box-shadow: 0px 25px 25px -15px #00b0c2;
  background: #00b0c2 !important;
  border: 0px !important;
  color: white;
}

.fair-phone-container:hover .fair-img-heading {
  color: white;
}
.fair-phone-container:hover .fair-content {
  color: white;
}
.fair-phone-container:hover .fair-explore-button {
  color: white;
}

.custom-project-first-heading {
  font-size: 22px;
  font-weight: bold;
  margin-left: 7rem;
  margin-bottom: 13px;
  font-family: "Raleway";
  margin-top: 37px;
}
.integration-text {
  margin-left: 7rem;
  margin-top: 0px;
  font-size: 16px;
  color: #8080809c;
  font-family: "Raleway";
}
.left-button {
  border: 1.5px solid #00b0c2;
  border-radius: 4px;
  box-shadow: 0 3px 15px 0px #00b0c24d !important;
  height: 33px;
  width: 132px;
  color: #00b0c2;
  background-color: transparent;
  font-family: "Raleway";
  margin-right: 5rem;
}
/* .custom-broject-container:hover {
  -webkit-box-shadow: 0px 25px 25px -15px #00b0c2;
  box-shadow: 0px 25px 25px -15px #00b0c2;
  background: #00b0c2 !important;
  border: 0px !important;
  color: white;
  transition: all 0.35s ease-Out;
}
.custom-broject-container:hover .left-button {
  background-color: #fff;
}
.custom-broject-container:hover .integration-text {
  color: #fff;
} */

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
.hvr-sweep-to-right:hover,
.hvr-sweep-to-right:focus,
.hvr-sweep-to-right:active {
  color: white;
}
.hvr-sweep-to-right:hover:before,
.hvr-sweep-to-right:focus:before,
.hvr-sweep-to-right:active:before {
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
.hvr-shadow:hover,
.hvr-shadow:focus,
.hvr-shadow:active {
  box-shadow: 0px 25px 25px -15px #69caf7;
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
.hvr-shadow:hover,
.hvr-shadow:focus,
.hvr-shadow:active {
  box-shadow: 0px 25px 25px -15px #8571ac;
}

@media only screen and (max-width: 1024px) {
      .carbotext-svg[data-v-1fe830de] {
    width: 42px;
    padding-left: 15px;
}
.app-text[data-v-1fe830de] {
    font-weight: bold;
    margin-left: 11px;
    font-size: 21px;
    font-family: "Raleway";
    /* font-weight: bold; */
    font-style: normal;
    font-weight: 600;
}
.circule[data-v-1fe830de] {
    color: #b7bfdd !important;
    font-size: 14px !important;
    margin-left: 17px !important;
}
.our-team-text[data-v-1fe830de] {
    font-style: normal;
    font-weight: normal;
    font-size: 16px !IMPORTANT;
    line-height: 22px;
    color: #9093a2;
    margin-top: 3px;
    margin-bottom: 10px;
    width: 717px;
    margin-left: 1rem;
    font-size: 12px;
    font-family: "Raleway";
}

.expo-container[data-v-1fe830de] {
  width: 355px;
    height: 323px;
    margin-left: 18px;
    border-radius: 4px;
    display: block !important;
    /* background-color: gray; */
    background-image: none !important;
    border: 2px solid #9e9e9e5c !important;
}
.explore-icon[data-v-1fe830de] {
    width: 40px;
    margin-right: 10px;
    border-radius: 4px;
    background-color: rgba(255, 255, 255, 0.25);
    padding: 5px;
    margin-left: 5%;
    margin-top: 13px;
    background-color: #9e9e9e4d;
}
.ticket-booth-heading[data-v-1fe830de] {
    text-overflow: ellipsis;
    font-size: 17px;
    color: #fff;
    margin-top: 11px;
    font-family: "Raleway";
    font-weight: bold;
    width: 168px;
    margin-left: 6%;
    color: black;
}
.explore-content[data-v-1fe830de] {
    font-size: 15px;
    margin-top: 9px;
    line-height: 28px;
    font-family: "Raleway";
    width: 64%;
    margin-left: 7%;
    color: gray;
}
.explore-button[data-v-1fe830de] {
    /* width: 165px; */
    height: 37px;
    font-size: 21px;
    color: #ffff;
    border: none;
    background-color: transparent;
    text-align: right;
    margin-left: 58%;
    margin-top: 56px;
    color: black;
}
.main-width[data-v-1fe830de] {
    width: 718px !important;
}
.fair-phone-container[data-v-1fe830de] {
    margin-top: 0px;
    margin-left: 18px !important;
    height: 322px;
    width: 345px;
        border-radius: 4px !important;
    border: 1px solid #9e9e9eab;
}
.fair-explore-button[data-v-1fe830de] {
    width: 110px;
    font-size: 18px;
    margin-top: 11px;
    border: none;
    background-color: transparent;
    margin-top: 101px;
}


}




@media only screen and (max-width: 767px) {
  .carbotext-svg {
    width: 59px !important;
    padding-left: 9px !important;
  }
  .circule {
    display: none;
  }
  .hr {
    display: none;
  }
  .our-team-text {
    font-style: normal;
    font-weight: normal !important;
    font-size: 16px !important;
    line-height: 24px !important;
    color: #9093a2;
    margin-top: 16px;
    margin-bottom: 10px;
    width: 330px !important;
    margin-left: 1rem;
    font-family: "Raleway";
  }
  .expo-container {
    display: none !important;
        height: 287px;
    width: 100% !important;
    margin: 0px auto;
    max-width: 331px;
    margin-left: 11px !important;
  }
  /* .fair-phone-container {
          margin-top: 0px;
    margin-left: 12px !important;
    height: 322px;
    width: 330px !important;
    border-radius: 4px !important;
    border: 1px solid #9e9e9eab;
    margin-top: 15px !important;
  } */
  /* .new-contant{
    margin-left: 16px !important;
    margin-top: 15px !important;
  } */
  .main-width {
    
   max-width: 100% !important;
    display: flex !important;
    flex-direction: column !important;
  }
  /* .fair-phone-container {
    height: 287px;
    width: 349px !important;
    margin: 0px auto;
  } */
  .fair-phone-secont-box {
    margin-left: 0px !important;
    margin-top: 16px !important;
  }
  .fair-phone-container[data-v-1fe830de][data-v-1fe830de] {
    margin-top: 12px !important;
    margin-left: 13px !important;
    height: 318px;
    width: 335px;
    border-radius: 4px !important;
    border: 1px solid #9e9e9eab;
}
 
 
}

</style>