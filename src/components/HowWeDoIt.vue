<template>
  <section class="how-main">
    <h2 class="doit" data-aos="zoom-in">How We Do It!</h2>
    <p class="intro" data-aos="zoom-in">We ONLY track animals upon registration. Registration is done through booking on our online platform. We will accept a minimum of 20 animals per booking. But you can book as many animals as you want.</p>
    <div class="howto">
      <div class="howto-content" data-aos="zoom-in">
         <img :src="registration" class="cowhead" data-aos="fade-down"/>
        <h3>Registration</h3>
        <p>Fill in a Biodata collection form in order to initiate the tracking Process.</p>
      </div>
      <div class="howto-content" data-aos="zoom-in">
         <img :src="payment" class="cowhead" data-aos="fade-down"/>
        <h3>Payment</h3>
        <p>A tracking fee of Ksh 5,000 only applies for each animal you register. If you register more than 100 animals we will give you a 40% discount per animal.</p>
      </div>
      <div class="howto-content" data-aos="zoom-in">
         <img :src="installation" class="cowhead" data-aos="fade-down"/>
        <h3>Installation</h3>
        <p>Our personnel in charge of tracking will visit you and place the tracking device on the selected animals within 7 working days.</p>
    </div>
    </div>
  </section>
</template>

<script>
import payment from '@/assets/images/payment.png'
import registration from '@/assets/images/registration.png'
import installation from '@/assets/images/tools.png'
import TrackNow from '@/components/TrackNow.vue'

export default {
  data: function () {
    return {
      payment: payment,
      registration: registration,
      installation: installation,
      components: {
        TrackNow
      }
    }
  }
}
</script>

<style scoped>
.how-main{
  max-width: 80%;
  margin: 2rem auto;
  padding: 2rem 0rem;
}

.how-main h2{
  color: red;
  font-weight: 600;
  font-size: 2rem;
  padding: 1rem 0rem;
}

.intro{
  font-size: 1.25rem;
  font-weight: 300;
  color: #2e3192;
  padding: 1rem 0rem;
}
.howto{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 3rem;
  justify-content: center;
  align-items: top;
  margin: 2rem 0rem;
}
@media screen and (max-width: 768px) {
  .howto{
    grid-template-columns: 1fr;
    gap: 2rem;
  }
}

.cowhead{
  width: 90px;
  background-color: #eeedf6;
  border-radius: 50%;
  padding: 1rem;
  margin: 1rem 0rem;
}
h3{
  color:#2e3192;
  padding: 1rem 0rem;
  font-size: 1.5rem;
  font-weight: 500;
}
</style>
