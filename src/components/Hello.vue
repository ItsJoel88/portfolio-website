<template>
  <div>
    <img src="../assets/100_0834.jpg" alt="photo-profile" width="170" height="170" id="pp" />
    <b-jumbotron header="Imanuel N Jodi" lead="Bootstrap v4 Components for Vue.js 2">
      <div class="row">
        <div class="col-md-6"></div>
        <div class="col-md-6" id="icon-list">
          <div id="icon-top">
            <img
              src="https://image.flaticon.com/icons/svg/145/145807.svg"
              alt="linkedin"
              width="30"
              height="30"
            />
            <img
              src="https://image.flaticon.com/icons/svg/2111/2111432.svg"
              alt="github"
              width="30"
              height="30"
            />
            <img
              src="https://about.gitlab.com/images/press/logo/png/gitlab-icon-rgb.png"
              alt="gitlab"
              width="40"
              height="40"
            />
          </div>
        </div>
      </div>
      <!-- <p>For more information visit website</p> -->
      <!-- <b-button variant="info" href="#">More Info</b-button> -->
    </b-jumbotron>
  </div>
</template>

<script>
export default {};
</script>

<style>
#pp {
  border-radius: 50%;
  position: absolute;
  margin-top: 4%;
  right: 0;
  margin-right: 12%;
}
#icon-top {
  text-align: right;
  padding-right: 24.5%;
}
#icon-top img:nth-child(2) {
  margin-right: 5px;
  margin-left: 12px;
}
#icon-list {
  margin-top: 3%;
}
</style>