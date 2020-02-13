<template>
  <div id="project-site">
    <div class="container" data-aos="fade-up">
      <div>
        <hr align="left" width="30%" class="line-text" color="white" />
        <h1 id="project">Project</h1>
        <hr align="right" width="30%" class="line-text" color="white" />
      </div>
      <b-container class="bv-example-row" id="container-project">
        <b-row class="first-row">
          <b-col sm="12" md="12" lg="4">
            <b-card
              title="Hoodie Hoo"
              img-src="https://i.imgur.com/L8r6Gw3.png"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>
                Main Technologies that I use :
                <ul>
                  <li>Vue & Vuex</li>
                  <li>Node JS</li>
                  <li>MongoDB</li>
                  <li>Google Cloud Platform</li>
                </ul>
              </b-card-text>

              <b-button href="http://e-commerce.itsjoel.site/" variant="primary" target="blank">Go !</b-button>
              <b-button
                href="https://github.com/ItsJoel88/e-commerce"
                variant="info"
                target="blank"
              >Github</b-button>
            </b-card>
          </b-col>
          <b-col sm="12" md="12" lg="4">
            <b-card
              title="Kanban Board"
              img-src="https://i.imgur.com/FTvZKkC.png"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>
                Main Technologies that I use :
                <ul>
                  <li>Vue & Vuex</li>
                  <li>Firebase Firestore</li>
                  <li>Vue Bootstrap</li>
                </ul>
              </b-card-text>

              <b-button
                href="https://kamvan-6aa69.firebaseapp.com/"
                variant="primary"
                target="blank"
              >Go !</b-button>
              <b-button
                href="https://github.com/ItsJoel88/kanban"
                variant="info"
                target="blank"
              >Github</b-button>
            </b-card>
          </b-col>
          <b-col sm="12" md="12" lg="4">
            <b-card
              title="HacktivOverflow"
              img-src="https://i.imgur.com/oWEThIK.png"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>
                Main Technologies that I use :
                <ul>
                  <li>Vue & Vuex</li>
                  <li>Node JS</li>
                  <li>MongoDB</li>
                  <li>Google Cloud Platform</li>
                </ul>
              </b-card-text>

              <b-button
                href="http://hacktivoverflow.itsjoel.site/"
                variant="primary"
                target="blank"
              >Go !</b-button>
              <b-button
                href="https://github.com/ItsJoel88/hacktivoverflow"
                variant="info"
                target="blank"
              >Github</b-button>
            </b-card>
          </b-col>
        </b-row>
        <b-row class="second-row">
          <b-col sm="12" md="12" lg="4">
            <b-card
              title="React Countries"
              img-src="https://i.imgur.com/iPJL7W0.png"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>
                Main Technologies that I use :
                <ul>
                  <li>React & Redux</li>
                  <li>Node JS</li>
                  <li>MongoDB</li>
                  <li>Google Cloud Platform & AWS EC2</li>
                </ul>
              </b-card-text>

              <b-button
                href="http://react-country.itsjoel.site/"
                variant="primary"
                target="blank"
              >Go !</b-button>
              <b-button
                href="https://github.com/ItsJoel88/react-challenge"
                variant="info"
                target="blank"
              >Github</b-button>
            </b-card>
          </b-col>
          <b-col sm="12" md="12" lg="4">
            <b-card
              title="Password Manager"
              img-src="https://i.imgur.com/sXiDWYL.png"
              img-alt="Image"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>
                Main Technologies that I use :
                <ul>
                  <li>React & Redux</li>
                  <li>Firebase Firestore</li>
                  <li>Google Cloud Functions</li>
                </ul>
              </b-card-text>

              <b-button
                href="https://password-manager-c211a.firebaseapp.com/"
                variant="primary"
                target="blank"
              >Go !</b-button>
              <b-button
                href="https://github.com/ItsJoel88/password-manager"
                variant="info"
                target="blank"
              >Github</b-button>
            </b-card>
          </b-col>
          <b-col sm="12" md="12" lg="4">
            <b-card
              title="School Dashboard"
              img-src="http://arika.org.uk/sites/default/files/uploads/News/upcoming.jpg"
              img-alt="Image"
              img-height="150"
              img-top
              tag="article"
              style="max-width: 20rem;"
              class="mb-2"
            >
              <b-card-text>Upcoming...</b-card-text>

              <b-button href="#project-site" variant="dark">Go !</b-button>
            </b-card>
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
@import url("https://fonts.googleapis.com/css?family=Montserrat:700&display=swap");
#project-site {
  padding-top: 1%;
}
#project {
  text-align: center;
  font-family: "Montserrat", sans-serif;
}
#container-project {
  margin-top: 3%;
  margin-bottom: 5%;
}
.second-row {
  margin-top: 3%;
}
.mb-2 {
  height: 70vh;
  transition: 0.3s ease-in-out;
  box-shadow: -1rem 0 3rem #000;
}
.card-text {
  height: 22vh;
}
.btn {
  margin-left: 2%;
}

@media only screen and (max-width: 800px) {
  .first-row,
  .second-row {
    text-align: center;
    width: 100%;
  }
  .mb-2 {
    margin-left: auto;
    margin-right: auto;
    height: 50vh;
  }
}
</style>
