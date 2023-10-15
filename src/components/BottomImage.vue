<template>
  <section class="bottom-image">
    <img :src="image" class="bottom-image" data-aos="fade-up"/>
  </section>
</template>

<script>
import ngombe from '@/assets/images/ngombe.jpg'

export default {
  data: function () {
    return {
      image: ngombe
    }
  }
}
</script>

<style scoped>
.bottom-image{
  width: 100%;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
  border-bottom: 1px solid #2e3192;
}
</style>
