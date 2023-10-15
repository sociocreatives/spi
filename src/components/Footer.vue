<template>
  <section class="footer-main-one">
    <div class="footer-main">
    <div>
        <p>Privacy Policy  |  Terms of Service</p>
    </div>
    <div>
        <p>&copy; {{ currentYear }} Safe Pastures Investments</p>
    </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Footer',
  data: function () {
    return {
      currentYear: new Date().getFullYear()
    }
  }
}
</script>

<style scoped>
.footer-main-one{
  max-width: 100%;
  background-color: #f0eff6;
}
.footer-main{
  max-width: 80%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 2rem 0rem;
  background-color: #f0eff6;
}
@media screen and (max-width: 768px) {
  .footer-main{
    flex-direction: column;
  }
}
</style>
```
