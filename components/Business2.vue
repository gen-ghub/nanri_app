<template>
  <section>
    <div class="grid grid-cols-2 h-80 bg-blue-500">
      <section class="business-wrapper bg-blue-200 h-56">
        <img class="h-full w-full animate__zoomInUp" src="~/assets/bbq1.jpg" />
        <a href="http://bbqdeli.jp/">
          <h1 class="business-title text-white text-4xl font-black">
            [関東]バーベキュー★デリ
          </h1>
        </a>
      </section>
      <section class="business-wrapper bg-blue-200 h-56">
        <img class="h-full w-full" src="~/assets/bbq2.jpg" />
        <a href="http://www.bbq-ranger.com">
          <h1 class="business-title text-white text-4xl font-black">
            　[関西]バーベキュー隊
          </h1>
        </a>
      </section>
      <section class="business-wrapper bg-blue-200 h-56">
        <img class="h-full w-full" src="~/assets/biru.jpg" />
        <a href="https://beerdeli.jp/">
          <h1 class="business-title text-white text-4xl font-black">
            　　　[ビールデリ]
          </h1>
        </a>
      </section>
      <section class="business-wrapper bg-blue-200 h-56">
        <img class="h-full w-full" src="~/assets/a.jpg" />
        <a href=" flashmob.biz">
          <h1 class="business-title text-white text-4xl font-black">
            　　　[ゼロモブ]
          </h1>
        </a>
      </section>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.business-wrapper{
  position: relative;

  .business-title{
    position: absolute;
    top: 80px;
    left: 200px;
  }
}
</style>
