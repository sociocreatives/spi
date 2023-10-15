<template>
  <section class="software-content-header">
    <div class="header">
      <img :src="ngamia" class="cowhead" data-aos="zoom-in"/>
      <h3>The Software</h3>
    </div>
    <div class="main-content" data-aos="zoom-in">
      <div>
        <p>Safe Pastures Investments has designed and developed a very unique software which is able to track animals using a special microchip that is injected under the animal’s skin. The microchips are certified to be safe both medically and scientifically for use in tracking all types of domestic animals e.g Cows, Goats, Sheep, Horses, Dogs, Pigs,e.t.c and also the wild animals. The microchip is then linked to a special and very sophisticated real time tracking software which makes it possible to track and trace the tagged animals on real time basis and give their geographical location.</p>
      </div>
       <div>
        <p class="pande" data-aos="zoom-in">We pride ourselves as the only custodians of a unique pet tracking system which uses special pet tracking microchips and a special tracking software to track and trace all types of animals both domestic and wild on a real time basis. <br/><br/>Apart from the tracking ability, the software also details the bio data of each animal and its owner, making it easy to precisely and accurately identify it in case the animal is lost and found.</p>
      </div>
    </div>
  </section>
</template>
<script>
import ngamia from '@/assets/images/SVG/gmap.svg'
export default {
  data: function () {
    return {
      ngamia: ngamia
    }
  }
}
</script>

<style scoped>
.software-content-header{
  max-width: 80%;
  margin: 3rem auto;
}
@media screen and (max-width: 768px) {
  .software-content-header{
    max-width: 80%;
    margin: 5rem auto;
  }
}

.main-content{
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 4rem;
  justify-content: space-between;
  align-items: top;
}
@media screen and (max-width: 768px) {
  .main-content{
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem;
  }
}
.cowhead{
  width: 7.5%;
  margin-bottom: 1rem;
}
@media screen and (max-width: 768px) {
  .cowhead{
    width: 15%;
    margin-bottom: 1rem;
  }
}

.header{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  margin-bottom: 2rem;
}
h3{
  font-weight: 600;
  font-size: 2rem;
  color: red;
  margin-bottom: 1rem;
}

.pande{
  border-left: solid 1px red;
  padding-left: 4rem;
}
@media screen and (max-width: 768px) {
  .pande{
    border-left: none;
    padding-left: 0rem;
  }
}
</style>
