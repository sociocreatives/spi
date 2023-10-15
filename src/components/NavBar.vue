<template>
  <section class="main-navbar">
      <nav class="navbar-main">
          <router-link to="/"><img :src="image" class="logo"/></router-link>
      <div>
      <div class="items">
          <router-link to="/">Home</router-link>
          <router-link to="/about">About</router-link>
          <router-link to="/software">Software</router-link>
          <router-link to="/contacts">Contact</router-link>
          <router-link to="/login" class="loginbutton">Login</router-link>
      </div>
      <img :src="navicon" class="icon" data-aos="fade-down" @click="showMenu()"/>
      </div>
    </nav>
  </section>

</template>

<script>
import logo from '@/assets/images/SVG/spi-logo.svg'
import navicon from '@/assets/images/navicon.png'

export default {
  data: function () {
    return {
      image: logo,
      navicon: navicon
    }
  }
}
</script>

<style scoped>
.main-navbar{
  border-bottom: #2e3192 .025rem solid;
  padding: 1rem 0rem;
  background-color: white;
  position: sticky;
  top: 0;
  z-index: 1000;
}
a{
  text-decoration: none;
  font-weight: 300;
  color: #2e3192;
}
a:hover{
  text-decoration: none;
  font-weight: 300;
  color: red;
  font-weight: 500;
}
.navbar-main{
  max-width: 90%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.items{
  display: flex;
  gap: 2rem;
  align-items: center;
}
@media screen and (max-width: 768px) {
  .items{
    display: none;
  }
}

.logo{
  width: 100px;
}
.loginbutton{
  background-color: #2e3192;
  color: #ffffff;
  padding: .75rem 2rem;
  border-radius: 2rem;
}
.loginbutton:hover{
  background-color: red;
  color: #ffffff;
  padding: .75rem 2rem;
  border-radius: 2rem;
}

.icon{
  width: 30px;
  display: none;
}
@media screen and (max-width: 768px) {
  .icon{
    display: block;
    width: 30px;
  }
}

.open-menu {
opacity: 1;
height: 150px;
}

.closed-menu {
opacity: 0;
height: 0;
padding: 0;
}

</style>
