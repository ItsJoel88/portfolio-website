<template>
  <div>
    <b-container class="bv-example-row">
      <b-row>
        <b-col>
          <div>
            <p>Permata Pamulang,South Tangerang</p>
            <p>0878-0823-4461</p>
            <p>imanuelnjodi@gmail.com</p>
            <iframe
              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15861.237258525067!2d106.7116703!3d-6.3539894!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69e585767db097%3A0xa70ea9506a9149e9!2zNsKwMjEnMTAuNyJTIDEwNsKwNDInNTIuMCJF!5e0!3m2!1sen!2sid!4v1578126186826!5m2!1sen!2sid"
              width="250"
              height="250"
              frameborder="0"
              style="border:0;"
              allowfullscreen
            ></iframe>
          </div>
        </b-col>
        <b-col>
          <div>
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
        </b-col>
        <b-col>
          <div>
            <form @submit.prevent="sendMessage">
              <input type="text" id="name" placeholder="Your Name." v-model="name" />
              <textarea
                cols="30"
                rows="10"
                id="message"
                placeholder="Your Message."
                v-model="message"
              ></textarea>
              <b-button type="submit" block variant="info">Send</b-button>
            </form>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "",
      message: ""
    };
  },
  methods: {
    sendMessage() {
      console.log(this.name);
      console.log(this.message);
    }
  }
};
</script>

<style>
#name,
#message {
  margin-bottom: 5%;
  display: block;
  width: 100%;
}
</style>
