<template>
  <div>
    <div class="flex-view flex-direction-col">
      <div class="flex-view flex-direction-row recommended-section">
        <div>
          <img class="recommended-svg" src="../assets/recommended-apps.svg" alt />
        </div>
        <div>
          <p class="recommended-heading">Recommended Apps</p>
        </div>
        <div class="flex-view flex-direction-row">
          <div>
            <i class="circule fa fa-circle" aria-hidden="true"></i>
          </div>
          <div class="hr"></div>
        </div>
      </div>
      <div>
        <p
          class="recommented-content"
        >Our team has gone through many programs while automating client workflows as well as our own. We have found that these apps have a strong balance between user-friendliness and API capability</p>
      </div>
    </div>
    <div class="flex-view flex-direction-row justify-content-c boxs-container mobile-responsive-boxes">
      <div class="flex-view flex-direction-col monday-box-container hvr-grow-shadow">
        <div>
          <img class="monday-svg" src="../assets/monday.png" alt />
        </div>
        <div>
          <p class="monday-heading">Monday.com</p>
        </div>
        <div>
          <p
            class="monday-content"
          >Manage everything in one workspace and give your team the flexibility it needs to build out a custom workflow.</p>
        </div>
        <div style="text-align: end;margin-top: 58px;margin-right: 30px;">
          <button class="monday-button">
            Explore
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </button>
        </div>
      </div>

      <div class="flex-view flex-direction-col monday-box-container hvr-grow-shadow">
        <div>
          <img class="monday-svg" src="../assets/dropbox.png" alt />
        </div>
        <div>
          <p class="monday-heading">Dropbox</p>
        </div>
        <div>
          <p
            class="monday-content"
          >Share and store files throughout your team, organize file access, and seamlessly collaborate on the same documents</p>
        </div>
        <div style="text-align: end;margin-top: 58px;margin-right: 30px;">
          <button class="monday-button">
            Explore
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </button>
        </div>
      </div>
      <div class="flex-view flex-direction-col monday-box-container hvr-grow-shadow">
        <div>
          <img class="monday-svg" src="../assets/pcrecruiter.png" alt />
        </div>
        <div>
          <p class="monday-heading">PCRecruiter</p>
        </div>
        <div>
          <p
            class="monday-content"
          >Track and manage your applicants throughout the placement process while showcasing your job openings.</p>
        </div>
        <div style="text-align: end;margin-top: 58px;margin-right: 30px;">
          <button class="monday-button">
            Explore
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </button>
        </div>
      </div>
    </div>
    <div class="flex-view flex-direction-row mobile-responsive-second-boxes tab-responsive Roni" >
      <div class="flex-view flex-direction-col monday-box-container hvr-grow-shadow boxes-width">
        <div>
          <img class="monday-svg" src="../assets/freshbooks.png" alt />
        </div>
        <div>
          <p class="monday-heading">FreshBooks</p>
        </div>
        <div>
          <p
            class="monday-content"
          >Track and manage your applicants throughout the placement process while showcasing your job openings on a job board that links back to the ATS.</p>
        </div>
        <div style="text-align: end;margin-top: 58px;margin-right: 30px;">
          <button class="monday-button  responsive-buttom">
            Explore
            <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </button>
        </div>
      </div>
      <div class="flex-view flex-direction-col monday-box-container hvr-grow-shadow boxes-width">
        <div>
          <img class="monday-svg" src="../assets/phoneburner.png" alt />
        </div>
        <div>
          <h2 class="monday-heading">PhoneBurnner</h2>
        </div>
        <div>
          <p
            class="monday-content"
          >Track and manage your applicants throughout the placement process while showcasing your job openings on a job board that links back to the ATS.</p>
        </div>
        <div style="text-align: end;margin-top: 58px;margin-right: 30px;">
          <button class="monday-button responsive-buttom">
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
  name: "recommended",
};
</script>
<style src="./recommended.css" scoped>

</style>

