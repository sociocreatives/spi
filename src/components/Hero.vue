<template>
  <section class="hero-main">
    <img :src="image" class="cowhead" data-aos="fade-down"/>
  </section>
</template>

<script>
import cow from '@/assets/images/safecows.jpg'
export default {
  name: 'Hero',
  data: function () {
    return {
      image: cow
    }
  }
}
</script>

<style scoped>
.hero-main{
  width: 100%;
  height: 80vh;
  background-color: #2e3192;
  display: flex;
  justify-content: center;
  align-items: center;
}
.cowhead{
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
