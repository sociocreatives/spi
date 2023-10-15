<template>
  <section class="map">
    <div class="map-section">
      <div>
        <h3>Contact Us</h3>
        <p>
          Vision Towers Muthithi Road,<br/>
          Westlands, Nairobi - Kenya<br/>
          Tel: +254 724 847 797<br/>
          info@spi.co.ke
        </p>
      </div>
      <div class="">
        <h3>Fill this form to Reach Us</h3>
    <form @submit.prevent="submitForm" v-if="!formSubmitted">
      <input
        v-model="name"
        type="text"
        placeholder="Enter your name"
      /><br>
      <input
        v-model="email"
        type="email"
        placeholder="Enter your email"
      /><br>
      <textarea
        class="textarea"
        line="5"
        v-model="message"
        type="textbox"
        placeholder="Enter your Message"
      /><br>
      <input
        class="submit"
        type="submit"
        value="Submit"
      >
    </form>
    </div>
    <div v-if="formSubmitted">
      <h3>Form Submitted</h3>
      <p>Name: {{ name }}</p>
      <p>Email: {{ email }}</p>
      <p>Gender: {{ gender }}</p>
      <small>Click on run to launch the app again.</small>
    </div>
  </div>
  </section>
</template>

<script>
export default {
  data () {
    return {
      name: '',
      email: '',
      gender: '',
      formSubmitted: false
    }
  },
  methods: {
    submitForm: function () {
      this.formSubmitted = true
    }
  }
}
</script>

<style scoped>
.map{
  max-width: 80%;
  margin: 5rem auto;
}

.map-section{
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
}
@media screen and (max-width: 768px) {
  .map-section{
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}
}

input {
  width: 100%;
  padding: .75rem 1rem;
  margin-bottom: .5rem;
}
h3{
  font-weight: 500;
  color: #2e3192;
  font-size: 1.5rem;
  padding-bottom: .5rem;
}

.textarea{
  width: 100%;
  padding: .75rem 1rem;
}
</style>
