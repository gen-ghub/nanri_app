<template>
  <section>
    <Slide />
    <TopExplanation />
    <Business />
    <!-- <Business2 /> -->
    <section class="h-full flex justify-center contact">
        <nuxt-link to="/Link03" class="block w-full flex justify-center m-2">
          <div>
            <h1 class="pt-32 pb-10">お問い合わせはこちらから</h1>
            <h3 class="pt-8 pb-32">　　　　Contact</h3>
          </div>
        </nuxt-link>
    </section>
  </section>

</template>

<script>
import Slide from '@/components/Slide.vue'
import TopExplanation from '@/components/TopExplanation.vue'
import Business from '../components/Business.vue'
import Business2 from '../components/Business2.vue'

export default {
  components: {
    Slide,
    TopExplanation,
    Business,
    Business2,
  },
}
</script>

<style lang="scss" scoped>
.contact{
  :hover{
    background-color: #022444;
    color: white;
  }
}
</style>
