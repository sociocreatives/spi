<template>
  <section class="sky-main">
    <img :src="ngamia" class="cowhead" />
  </section>
</template>
<script>
import ngamia from '@/assets/images/sky.jpg'
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
