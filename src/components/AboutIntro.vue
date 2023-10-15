<template>
  <section class="about-header">
    <div class="header-content" data-aos="zoom-in">
      <img :src="image2" class="cowhead" data-aos="zoom-in"/>
      <p class="about-top">WHO WE ARE?</p>
      <h3>Start Tracking with Us</h3>
      <p>Safe Pastures Investments abbreviated as SPI is a company which uses safe pet microchips to tag, track and trace all types of domestic animals i.e cows, goats, sheep, camels, horses, donkeys, pigs, dogs, among others. We pride ourselves as the only custodians of a unique pet tracking system which uses special pet tracking microchips and a special tracking software to track and trace all types of domestic animals in a real-time.</p>
      <br/>
      <p>Ours is a next level discovery and innovation only found at SPI. This is a game changer in the fight against banditry and cattle rustling, as well as in ensuring safety and security of our animals in general.</p>
    </div>
  </section>
</template>

<script>
import cowhead from '@/assets/images/SVG/faras.svg'
export default {
  data: function () {
    return {
      image2: cowhead
    }
  }
}
</script>

<style scoped>
.about-header{
  max-width: 55%;
  margin: 5rem auto;
  text-align: center;
}
@media (max-width: 768px) {
  .about-header{
    max-width: 80%;
    margin: 5rem auto;
    text-align: center;
  }
}
.cowhead{
  width: 25%;
}
@media screen and (max-width: 768px) {
  .cowhead{
    width: 50%;
  }
}
.about-top{
  padding: .5rem 0rem;
  letter-spacing: .25rem;
  color: #2e3192;
}
h3{
  font-weight: 600;
  font-size: 2rem;
  color: red;
  margin-bottom: 1rem;
}
</style>
