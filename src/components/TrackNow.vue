<template>
  <section class="tracknow">
    <div class="interested" data-aos="zoom-in">
     <div>
      <p class="small">ALREADY INTERESTED?</p>
      <h2>Lets Track Your Animal for you</h2>
      <p>Tell us about your request, and we'll get in touch with next steps.</p>
    </div>
    <button class="tracking-button" data-aos="zoom-in">Get Started</button>
    </div>
  </section>
</template>

<style scoped>

.tracknow{
  width: 80%;
  margin: 1rem auto;
  color: #ffffff;
}
.interested{
  background-color: #2e3192;
  padding: 5rem 5rem;
  border-radius: 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
@media screen and (max-width: 768px) {
  .interested{
    flex-direction: column;
    padding: 2rem 3rem;
    justify-content: center;
    align-content: center;
    text-align: center;
  }
}

h2{
  font-weight: 600;
  font-size: 2rem;
  color: #eeedf0;
}
@media screen and (max-width: 768px) {
  h2{
    font-weight: 600;
    font-size: 1.5rem;
    color: #eeedf0;
    padding-bottom: 2rem;
  }
}

.small{
  padding: 1rem 0rem;
  letter-spacing: .25rem;
}

p{
  letter-spacing: .10rem;
  padding-bottom: 1rem;
}

.tracking-button{
    margin: 1rem 0rem;
    padding: 1rem 3rem;
    border-radius: 2rem;
    border: none;
    font-size: 1.1rem;
    background-color: #ffffff;
    color: #2e3192;
    cursor: pointer;
  }

  @media screen and (max-width: 768px) {
    .tracking-button{
      margin: 1rem 0rem;
      padding: 1rem 3rem;
      border-radius: 2rem;
      border: none;
      font-size: 1.1rem;
      background-color: #ffffff;
      color: #2e3192;
      cursor: pointer;
      width: 100%;
    }

  }

  .tracking-button:hover{
    margin: 1rem 0rem;
    padding: 1rem 3rem;
    border-radius: 2rem;
    border: none;
    font-size: 1.1rem;
    background-color: red;
    color: white;
    cursor: pointer;
  }
</style>
