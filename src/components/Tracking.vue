<template>
  <div class="main">
  <section class="tracking-main">
     <div>
        <img :src="image" class="bulb" data-aos="fade-down"/>
        <h1 class="tracking-header" data-aos="zoom-in">Did You Know?</h1>
        <p class="tracking-info" data-aos="zoom-in">That you can Track your Cow in Real Time and Trace it's movements everytime everyday 24/7.</p>
        <p class="tracking-content" data-aos="zoom-in">We pride ourselves as the only custodians of a unique pet tracking system which uses special pet tracking microchips and a special tracking software to track and trace all types of animals both domestic and wild on a real time basis.</p>
        <button class="tracking-button" data-aos="zoom-in">Start Tracking with Us</button>
    </div>
    <div>
      <img :src="image2" class="camel" data-aos="fade-down"/>
    </div>
    </section>
  </div>
</template>

<script>
import bulb from '@/assets/images/SVG/bulb.svg'
import camel from '@/assets/images/Camels2.jpg'

export default {
  data: function () {
    return {
      image: bulb,
      image2: camel
    }
  }
}
</script>

<style scoped>
  .tracking-main{
    width: 80%;
    margin: 1rem auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-content: center;
    align-items: center;
    gap: 5rem;
  }
  @media screen and (max-width: 768px) {
    .tracking-main{
      grid-template-columns: 1fr;
      gap: 2rem;
    }
  }
  .tracking-header{
    font-size: 2.5rem;
    font-weight: 300;
    color: red;
  }
  .tracking-info{
    font-size: 1.5rem;
    font-weight: 500;
    color: #2e3192;
    padding: 1rem 0rem;
  }

  .tracking-button{
    margin: 1.5rem 0rem;
    padding: 1rem 3rem;
    border-radius: .5rem;
    border: none;
    font-size: 1.1rem;
    background-color: #2e3192;
    color: white;
    cursor: pointer;
  }

  @media screen and (max-width: 768px) {
    .tracking-button{
      margin: 1rem 0rem;
      padding: 1rem 3rem;
      border-radius: .5rem;
      border: none;
      font-size: 1.1rem;
      background-color: #2e3192;
      color: white;
      cursor: pointer;
      width: 100%;
    }

  }

  .tracking-button:hover{
    margin: 1rem 0rem;
    padding: 1rem 3rem;
    border-radius: .5rem;
    border: none;
    font-size: 1.1rem;
    background-color: red;
    color: white;
    cursor: pointer;
  }

  .bulb{
    width: 80px;
    margin-bottom: 1rem;
  }
  .camel{
    width: 100%;
    border-radius: 2rem;
  }

  .main{
        background-color: #f0eff6;
        padding: 3rem 0rem;
  }

</style>
