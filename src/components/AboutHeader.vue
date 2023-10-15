<template>
  <section class="header">
    <img :src="image" class="bottom-image" data-aos="fade-up"/>
  </section>
</template>

<script>
import green from '@/assets/images/green-field.jpg'

export default {
  data: function () {
    return {
      image: green
    }
  }
}
</script>

<style scoped>
.header {
  width: 100%;
}
.bottom-image{
  width: 100%;
}
</style>
