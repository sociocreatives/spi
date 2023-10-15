<template ref="target">
  <div>
    <Hero/>
    <Intro/>
    <Divider/>
    <Tracking/>
    <HowWeDoIt/>
    <TrackNow/>
    <BottomImage/>
     <BottomContacts/>
    <Divider/>
  </div>
</template>

<script>
import Hero from '@/components/Hero.vue'
import Intro from '@/components/Intro.vue'
import Tracking from '@/components/Tracking.vue'
import Divider from '@/components/Divider.vue'
import HowWeDoIt from '@/components/HowWeDoIt.vue'
import TrackNow from '@/components/TrackNow.vue'
import BottomImage from '@/components/BottomImage.vue'
import BottomContacts from '@/components/BottomContacts.vue'

export default {
  name: 'Home',
  components: {
    Hero,
    Intro,
    Divider,
    Tracking,
    HowWeDoIt,
    TrackNow,
    BottomImage,
    BottomContacts
  }

}
</script>

<style scoped>

</style>
