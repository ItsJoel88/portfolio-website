<template>
  <div id="contact">
    <div class="container" data-aos="fade-up">
      <div>
        <hr align="left" width="30%" class="line-text" color="white" />
        <h1 id="project">Contact</h1>
        <hr align="right" width="30%" class="line-text" color="white" />
      </div>
      <b-container class="bv-example-row">
        <b-row>
          <b-col md="12" lg="6">
            <div class="footer">
              <iframe
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15861.237258525067!2d106.7116703!3d-6.3539894!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69e585767db097%3A0xa70ea9506a9149e9!2zNsKwMjEnMTAuNyJTIDEwNsKwNDInNTIuMCJF!5e0!3m2!1sen!2sid!4v1578126186826!5m2!1sen!2sid"
                width="350"
                height="250"
                frameborder="0"
                style="border:0;"
                allowfullscreen
              ></iframe>
              <div class="location-map">
                <img
                  src="https://image.flaticon.com/icons/svg/854/854878.svg"
                  alt="location"
                  height="30"
                  width="30"
                />
                <h5>Permata Pamulang,South Tangerang</h5>
              </div>
              <div class="phone">
                <img
                  src="https://image.flaticon.com/icons/png/512/1429/1429878.png"
                  alt="phone"
                  width="30"
                  height="30"
                />
                <h5>0878-0823-4461</h5>
              </div>
            </div>
          </b-col>
          <b-col id="second-col" md="12" lg="6">
            <div class="list-icon">
              <a
                href="https://mail.google.com/mail/?view=cm&fs=1&to=imanuelnjodi@gmail.com"
                target="blank"
              >
                <img
                  src="https://image.flaticon.com/icons/svg/732/732200.svg"
                  alt="gmail"
                  width="30"
                  height="30"
                />
                imanuelnjodi@gmail.com
              </a>
              <a href="https://www.linkedin.com/in/imanuel-n-jodi-633536108/" target="blank">
                <img
                  src="https://image.flaticon.com/icons/svg/145/145807.svg"
                  alt="linkedin"
                  width="30"
                  height="30"
                />
                Imanuel N Jodi
              </a>

              <a href="https://github.com/ItsJoel88" target="blank">
                <img
                  src="https://image.flaticon.com/icons/svg/2111/2111432.svg"
                  alt="github"
                  width="30"
                  height="30"
                />
                ItsJoel88
              </a>
              <a href="https://gitlab.com/ItsJoel88" target="blank">
                <img
                  src="https://about.gitlab.com/images/press/logo/png/gitlab-icon-rgb.png"
                  alt="gitlab"
                  width="30"
                  height="30"
                />
                ItsJoel88
              </a>
            </div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
h5 {
  color: white;
}
.container {
  padding: 1%;
}
#name,
#message {
  margin-bottom: 5%;
  display: block;
  width: 100%;
}
.line-text {
  border: 2px solid rgba(0, 0, 0, 0.1);
}

.list-icon {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.list-icon a {
  padding: 7px;
  text-decoration: none;
  display: flex;
  flex-direction: column;
  text-align: center;
  align-items: center;
  border-radius: 4px;
  background-color: #202026;
  color: white;
  width: 60%;
  margin-bottom: 3%;
  transition: 0.2s ease-in-out;
  box-shadow: -1rem 0 3rem #000;
}
.list-icon a:hover {
  text-decoration: none;
  color: white;
}
.phone,
.location-map {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
}
.phone img,
.location-map img {
  margin-right: 2%;
}

@media only screen and (max-width: 800px) {
  #second-col {
    margin-top: 3%;
  }
}
</style>
