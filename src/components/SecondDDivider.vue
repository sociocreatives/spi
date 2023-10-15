<template>
  <section class="divider">

  </section>
</template>

<script>
import ngamia from '@/assets/images/ngamia.jpg'
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
.divider{
  border-bottom: #2e3192 1px solid;
}
</style>
