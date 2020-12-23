<template>
  <section>
    <Slide />
    <TopExplanation />
    <section class="item bg-gray-300 ">
      <div class="">
        <section class="m-auto w-4/5 h-full">
          <h2 class="flex flex-wrap content-center justify-center h-40">概要＿事業内容＿タイトル</h2>
        </section>
        <div class=" w-4/5 h-full m-auto">
          <section class=" flex justify-evenly">
            <section>
              <a href="http://bbqdeli.jp/">
                <img class="h-56 w-56" src="~/assets/bbq1.jpg" />
              </a>
              <h1 class="">[関東]バーベキュー★デリ</h1>
              <p>東京を中心にBBQの設備レンタルをしています。</p>
            </section>
            <section>
              <a href="http://www.bbq-ranger.com">
                <img class="h-56 w-56" src="~/assets/bbq2.jpg" />
              </a>
              <h1 class="">[関西]バーベキュー隊</h1>
              <p>大阪を中心にBBQの設備レンタルをしています。</p>
            </section>
            <section>
              <a href="https://beerdeli.jp/">
                <img class="h-56 w-56" src="~/assets/biru.jpg" />
              </a>
              <h1 class="">[ビールデリ] </h1>
              <p>野外でビールをお楽しみ頂いております。</p>
            </section>
            <section>
              <a href=" flashmob.biz">
                <img class="h-56 w-56" src="~/assets/a.jpg" />
              </a>
              <h1 class="">[ゼロモブ] </h1>
              <p>ブライダルの余興を盛り上げます。</p>
            </section>
          </section>
        </div>
      </div>
    </section>
  </section>
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
  height: 70vh;
  width: 100%;
}
</style>
