<template ref="target">
  <div>
    <AboutIntro/>
    <AboutHeader/>
    <Mission/>
    <SecondDivider/>
    <HowWeDoIt/>
    <TrackNow/>
    <BottomImage/>
    <BottomContacts/>
    <Divider/>
  </div>
</template>

<script>
import AboutHeader from '@/components/AboutHeader.vue'
import AboutIntro from '@/components/AboutIntro.vue'
import Mission from '@/components/Mission.vue'
import SecondDivider from '@/components/SecondDDivider.vue'
import Divider from '@/components/Divider.vue'
import HowWeDoIt from '@/components/HowWeDoIt.vue'
import TrackNow from '@/components/TrackNow.vue'
import BottomImage from '@/components/BottomImage.vue'
import BottomContacts from '@/components/BottomContacts.vue'

export default {
  name: 'Home',
  components: {
    AboutHeader,
    AboutIntro,
    Mission,
    SecondDivider,
    HowWeDoIt,
    TrackNow,
    BottomImage,
    BottomContacts,
    Divider
  }

}
</script>

<style scoped>

</style>
