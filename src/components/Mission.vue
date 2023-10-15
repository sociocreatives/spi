<template>
  <section class="mission">
    <div class="mission-content" data-aos="zoom-in">
      <h3>Vision</h3>
      <p>To use high level technology to track and trace all kinds of domestic animals in order to end rampant animal theft, banditry and cattle rustling.</p>
    </div>
    <div class="mission-content" data-aos="zoom-in">
      <h3>Mission</h3>
      <p>To be a leading provider of safe and reliable pet micro-chipping services to the domestic livestock farmers and in Kenya and the entire East Africa region, with an aim of securing livestock and maximizing return on investment for the farmers and other stakeholders.</p>
    </div>
  </section>
</template>

<style scoped>
.mission{
  max-width: 80%;
  margin: 5rem auto;
  display: flex;
  gap: 4rem;
  justify-content: space-between;
  align-items: center;
}
@media screen and (max-width: 768px) {
  .mission{
    max-width: 80%;
    margin: 5rem auto;
    display: flex;
    flex-direction: column;
    gap: 4rem;
    justify-content: space-between;
    align-items: center;
  }
}
h3{
  font-weight: 600;
  font-size: 1.5rem;
  color: #2e3192;
  margin-bottom: 1rem;
}
.mission-content{
  border-left: 1px solid red;
  padding-left: 2rem;
}
</style>
