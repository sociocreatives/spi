<template>
  <section class="software-header">
    <img :src="ngamia" class="cowhead" />
  </section>
</template>

<script>
import ngamia from '@/assets/images/horses.jpg'
export default {
  data: function () {
    return {
      ngamia: ngamia
    }
  }
}
</script>

<style scoped>
.cowhead{
  width: 100%;
}
@media screen and (max-width: 768px) {
  .cowhead{
    width: 100%;
  }
}
</style>
