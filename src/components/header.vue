<template>
  <div class="flex-view flex-direction-row justify-content-b">
    <div class="flex-view flex-direction-row">
      <router-link to="/home">
        <div class="flex-view flex-direction-row justify-content-b">
          <img class="nav-logo" src="../assets/logo.svg" alt />
          <!-- <img class="navbar-logo" src="../assets/navbar-logo.svg" alt=""> -->
          <img class="navbar-logo" src="../assets/navbar-logo.svg" alt="">

          <div class="hamburger"><i class="fa fa-bars" aria-hidden="true" onclick="myfunction"></i></div>
        </div>
      </router-link>

      <div>
        <button class="demo-button hvr-sweep-to-right">DEMO</button>
      </div>

      <div>
        <button class="suport-button hvr-sweep-to-bottom">SUPPORT</button>
      </div>
    </div>
    <div
      class="flex-view flex-direction-row justify-content-b Nav-bar"
      style="width: 610px; font-size: 16px;"
    >
     <router-link to="/home">
        <div class="nav-style">
        <i class="fa fa-home home" aria-hidden="true"></i>Home
      </div>
     </router-link>
      <div class="nav-style first-dropdown">
        <i class="fa fa-users about" aria-hidden="true"></i>About us
        <div class="flex-view flex-direction-col drop-content">
          <a href="#">ABOUT US</a>
          <br />
          <a href="#">PORTFOLIO</a>
        </div>
      </div>

      <div class="nav-style Pop-Up">
        <i class="fa fa-globe service" aria-hidden="true"></i>Service
        <div class="flex-direction-row flex-view">
          <div
            class="flex-view flex-direction-row justify-content-b fourth-dropdown-content service-2"
          >
            <div class="BSITT flex-view flex-directon-row justify-content-b">
              <div class="flex-view flex-direction-row Concept-Production">
                <div class="flex-view flex-direction-row first-icon">
                  <div class="first">
                    <img style="    width: 40px;height: 44px;padding-bottom: 10px;" class="first" src="../assets/carban.png" alt />
                  </div>
                  <div class="concept">
                    <p style="    margin: 0px auto;margin-left: 11px;">Concept Production</p>

                    <p class="parem-1">Streamline your process with integrations.</p>
                  </div>
                </div>
              </div>
              <div class="flex-view flex-direction-row">
                <div class="flex-view flex-direction-row secoond-icon">
                  <div>
                    <img style="    width: 40px;height: 44px;padding-bottom: 10px;" src="../assets/carban2.png" alt />
                  </div>
                  <div class="Developmenttttt">
                    <p style="margin:0px auto; text-align: left;margin-left: 32px;">Development</p>
                    <p
                      class="parem"
                    >Streamline your process with integrations and workflow automation.</p>
                  </div>
                </div>
              </div>
              <div class="flex-view flex-direction-row Integrations-box">
                <div class="flex-view flex-direction-row three">
                  <div class="three">
      <router-link to="/teamIntegrations">
                    <img style="    width: 40px;height: 44px;padding-bottom: 10px;" src="../assets/carban3.png" alt />

      </router-link>
                      
                  </div>
                  <div class="Integrationsssss">
      <router-link to="/teamIntegrations">

                    <p style="margin:0px auto; text-align: left;margin-left: 32px;">Integrations</p>
                    <p
                      class="parem"
                    >Streamline your process with integrations and workflow automation.</p>
      </router-link>
                  </div>
                </div>
              </div>
              <div class="flex-view flex-direction-row Data-Management">
                <div class="flex-view flex-direction-row four">
                  <img style="    width: 40px;height: 44px;padding-bottom: 10px;" src="../assets/carban4.png" alt />
                  <div class="Data">
                    <p style="margin:0px auto; text-align: left;margin-left: 32px;">Data Management</p>

                    <p
                      class="parem"
                    >Streamline your process with integrations and workflow automation.</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="nav-style second-dropdown">
        <i class="fa fa-object-ungroup product" aria-hidden="true"></i>
        product
        <div class="flex-view flex-direction-col drop-content-two">
          <a href="#">APP NETWORK</a>
        </div>
      </div>
      <div class="nav-style third">
        <i class="fa fa-lightbulb-o resorce" aria-hidden="true"></i>
        Reserce
        <div class="flex-view flex-direction-col last-dropdown-content">
          <a class="roni" href="#">BLOG</a>
          <br />
          <a href="#">SPORT</a>
          <br />
          <a href="#">STUDIO</a>
        </div>
      </div>
    </div>
    <div class="flex-view flex-direction-col responsive-menu">
      <div>Home</div>
       <div>Service</div>
        <div>Integration</div>
         <div>About</div>

    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";


export default {
  name: "header",
};
</script>
<style src="./header.css" scoped>



</style>