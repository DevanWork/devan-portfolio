<template>
  <div class="page">
    <b-card no-body class="cardPage">
      <b-card-body class="home-header">
        <h1>Home</h1>
      </b-card-body>

      <b-card-body class="home-body">
        <b-card-title class="home-padding"
          >This site contains most information regarding Devan
          Chaney.</b-card-title
        >
        <b-card-text class="home-info home-padding">
        Here you will find: <br>» About Section <br>» Portfolio Showcasing
          Indepentdant Projects <br>» Up to Date Resume and Certificates <br>» Wide
          Range of Artifacts from the Gaming, Interactive Media, and Mobile
          Technology Major
        </b-card-text>

        <img src="@/assets/Profile.png" alt="Devan Chaney" class="home-pic"/>


        <br><br>


      </b-card-body>

      <b-card-footer class="home-footer">
        Copyright © 2023 DEVAN CHANEY, All rights reserved.
      </b-card-footer>
    </b-card>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.cardPage {
  max-width: 100vw;
  min-height: 100vh;
  height: 100vh;
}

.home-header {
  text-align: center;
  background-color: #3ab67b;
  color: white;
  min-height: 10vh;
  max-height: 10vh;
}

.home-body {
  background-color: #cbffe6;
  overflow-y: auto;
  text-align: center;
}

.home-footer {
  text-align: center;
  background-color: #3ab67b;
  color: white;
}

.home-info {
    font-size: 20px;
}

.home-padding {
    margin-bottom: 5vh;
}

.home-pic {
  width: 20vw;
  height: 47vh;
  margin: auto;
}
</style>