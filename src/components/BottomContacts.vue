<template>
  <section class="bottom-main">
    <div class="intro">
      <h3>About Us</h3>
      <p>Safe Pastures Investments abbreviated as SPI is a company which uses safe pet microchips to tag, track and trace all types of domestic animals i.e cows, goats, sheep, camels, horses, donkeys, pigs, dogs, among others.</p>
    </div>
    <div class="intro">
    </div>
    <div class="intro">
      <h3>Contact Us</h3>
      <p>Vision Towers Muthithi Road,</p>
      <p>Westlands, Nairobi - Kenya</p>
      <p>Tel: +254 724 847 797</p>
      <p>info@spi.co.ke</p>
    </div>
  </section>
</template>

<style scoped>
.bottom-main{
  width: 80%;
  margin: 1rem auto;
  padding: 4rem 0rem;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 2rem;
  justify-content: center;
  align-items: top;
}

@media screen and (max-width: 768px) {
  .bottom-main{
    grid-template-columns: 1fr;
    gap: 2rem;
  }
}

h3{
  font-weight: 500;
  color: #2e3192;
  font-size: 1.5rem;
  padding-bottom: .5rem;
}
</style>
