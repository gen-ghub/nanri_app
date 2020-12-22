<template>
  <div>
    <Slide />
    <TopExplanation />
    <div class="item bg-gray-300">
      <p class="pb-24 leading-loose">
        だからこそ、あえて言いたい。<br />
        先生は、自由だ。先生には、可能性が溢れている。<br />
        教え方にルールもない。一人一人に合ったやり方がある。
      </p>
    </div>
  </div>
</template>

<script>
import Slide from "@/components/Slide.vue";
import TopExplanation from "@/components/TopExplanation.vue";

export default {
  components: {
    Slide,
    TopExplanation
  }
};
</script>


<style lang="scss" scoped>

.item {
  height: 50vh;
  width: 100%;
}
</style>
