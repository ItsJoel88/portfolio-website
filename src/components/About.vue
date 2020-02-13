<template>
  <div id="about">
    <div class="container">
      <div>
        <hr align="left" width="30%" class="line-text" color="white" />
        <h1 id="project">About Me</h1>
        <hr align="right" width="30%" class="line-text" color="white" />
      </div>
      <div class="text-container">
        <div class="about-container" data-aos="fade-up">
          <div class="left-side">
            <h3 id="imanuel">Imanuel N Jodi</h3>
            <p>Hello, I am Imanuel, web-developer based on South Tangerang. I have experience in web site design & building and customization. Also I am good at</p>
            <div class="skill">
              <span>Javascript</span>
              <span>CSS</span>
              <span>HTML</span>
              <span>PHP</span>
              <span>SQL</span>
              <span>NoSQL</span>
              <span>Vue</span>
              <span>React</span>
              <span>Laravel</span>
            </div>
          </div>
          <div class="right-side">
            <img src="../assets/100_0834.png" alt="photo-profile" width="170" height="170" id="pp" />
            <div class="download-cv">
              <img
                src="https://image.flaticon.com/icons/svg/960/960563.svg"
                alt="download"
                height="30"
                width="30"
              />
              <a
                href="https://drive.google.com/file/d/1zC2B2L72JalA1kiRxidoHMaFXwS2G0TQ/view"
                target="blank"
              >Download CV</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:700&display=swap");
#about {
  padding-top: 1%;
}
.container {
  font-family: "Montserrat", sans-serif;
  margin-top: 5%;
}
.about-container {
  border-radius: 15px;
  color: black;
  background-color: white;
  /* background-color: #202026; */
  width: 65%;
  margin-left: auto;
  margin-right: auto;
  height: 75vh;
  box-shadow: -1rem 0 3rem #000;
  display: flex;
  flex-direction: row;
}
.left-side {
  margin-left: 2%;
  /* background-color: rebeccapurple; */
  width: 50%;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.left-side p {
  font-size: 14px;
  padding: 4px;
}
.skill {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
}
.skill span {
  border: 2px solid grey;
  margin-right: 5%;
  margin-bottom: 2.5%;
  padding: 4px;
  border-radius: 6px;
}
.right-side {
  width: 50%;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.right-side a {
  padding: 8px;
  color: white;
  text-decoration: none;
  /* border: 1px solid white;
  padding: 8px;
  border-radius: 20px;
  background-color: #202026; */
}
.right-side .download-cv {
  border: 1px solid white;
  padding: 8px;
  border-radius: 20px;
  background-color: #202026;
}
.right-side a:hover {
  color: white;
  text-decoration: none;
}
#pp {
  border-radius: 50%;
  margin-bottom: 4%;
}
#imanuel {
  border-bottom: 2px solid black;
  width: 70%;
  margin-left: auto;
  margin-right: auto;
}

@media only screen and (max-width: 800px) {
  .about-container {
    height: 50vh;
  }
}
</style>