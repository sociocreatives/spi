<template>
  <section class="mission">
    <div class="mission-content" data-aos="zoom-in">
      <h3>Clientelle</h3>
      <p>Safe Pastures Investments targets to sell its services to individuals, groups of people, institutions, organizations, National government of Kenya, County Governments, especially in North Rift regions that are adversely affected by banditry and cattle rustling.</p>
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
