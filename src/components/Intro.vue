<template>
  <section class="intro-section">
    <div class="intro-text">
      <img :src="image2" class="cowhead" data-aos="fade-down"/>

      <h4 class="intro-header" data-aos="zoom-in">Our Brief Intro..</h4>
      <p class="safe" data-aos="zoom-in">Safe Pastures Investments abbreviated as SPI is a company which uses safe pet microchips to tag, track and trace all types of domestic animals i.e cows, goats, sheep, camels, horses, donkeys, pigs, dogs, among others.</p>

    </div>
  </section>

</template>

<script>
import cow from '@/assets/images/cow.png'
import cowhead from '@/assets/images/SVG/cowhead.svg'
import fence from '@/assets/images/SVG/fence.svg'

export default {
  data: function () {
    return {
      image: cow,
      image2: cowhead,
      image3: fence
    }
  }
}
</script>

<style scoped>
.cows{
  width: 500px;
}

.intro-section{
  text-align: center;
  width: 60%;
  margin: 5rem auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 4rem;
}
@media (max-width: 768px) {
  .intro-section{
    flex-direction: column;
    width: 90%;
  }
}

.intro-text{
  padding: 1rem;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.safe{
  line-height: 2rem;
  font-size: 1.25rem;
}

.btn{
  text-align: center;
  background-color: #2e3192;
  font-weight: 200;
  color: white;
  width: fit-content;
  padding: .5rem 2rem;
  border-radius: 3rem;
}

.intro-header{
  color: #2e3192;
  font-weight: 600;
  font-size: 2rem;
  padding: 1rem 0rem;
}

.cowhead{
  width: 8%;
}
@media screen and (max-width: 768px) {
  .cowhead{
    width: 20%;
  }
}

.fence{
  width: 700px;
  margin: 2rem 0rem;

}
@media screen and (max-width: 768px) {
  .fence{
    width: 100%;
  }
}

</style>
