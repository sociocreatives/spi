<template ref="target">
  <div>
    <SoftwareContent/>
    <SoftwareHeader/>
    <SoftwareClients/>
    <SecondDivider/>
    <HowWeDoIt/>
    <TrackNow/>
    <BottomImage/>
    <BottomContacts/>
    <Divider/>
  </div>
</template>

<script>
import Sky from '@/components/Sky.vue'
import SoftwareHeader from '@/components/SoftwareHeader.vue'
import SoftwareClients from '@/components/SoftwareClients.vue'
import SoftwareContent from '@/components/SoftwareContent.vue'
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
    Sky,
    SoftwareHeader,
    SoftwareClients,
    SoftwareContent,
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
