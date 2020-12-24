<template>
  <section class="bg-gray-300 h-full py-10">
    <div class="">
      <section class="m-auto w-4/5">
        <h2 class="flex flex-wrap content-center justify-center h-40 text-2xl">
          概要＿事業内容＿タイトル
        </h2>
      </section>
      <section class="m-auto w-4/5 mb-8">
        <div class="itme p-8 rounded flex flex-wrap content-center justify-center space-x-32 h-60">
          <img class="h-56 w-3/12 rounded" src="~/assets/bbq1.jpg" />
          <section>
            <h3 class="py-8">関東(東京、神奈川、埼玉、千葉)でBBQ設備レンタルをしています。</h3>
            <h3 class="pb-12">関西(大阪、兵庫、京都、奈良、滋賀、和歌山、三重)でBBQ設備レンタルをしています。</h3>
            <a class="ml-16 mr-20 bg-red-600 p-2 rounded text-white hover:bg-red-400 " href="http://bbqdeli.jp/">[関東]バーベキュー★デリ</a><a class="bg-yellow-500 p-2 rounded text-white hover:bg-yellow-300" href="http://www.bbq-ranger.com">関西]バーベキュー隊</a>
          </section>
        </div>
      </section>
      <section class="">
        <div class="grid grid-cols-2">
          <div class="flex flex-wrap content-center justify-center">
            <section>
              <div class="itme rounded bg-gray-50 p-10 ml-16 shadow-2xl ">
                <div class="flex flex-wrap content-center justify-center"><img class="h-56 w-56 rounded" src="~/assets/biru.jpg" /></div>
                <div><p class="mb-8">野外でビールをお楽しみ頂いております。</p></div>
                <div class="flex flex-wrap content-center justify-center"><a class=" bg-yellow-600 p-2 rounded text-white hover:bg-yellow-400 " href="https://beerdeli.jp/">[ビールデリ]</a></div>
              </div>
            </section>
          </div>
          <div class="flex flex-wrap content-center justify-center">
            <section>
              <div class="itme rounded bg-gray-50 p-10 mr-16 shadow-2xl ">
                <div class="flex flex-wrap content-center justify-center"><img class="h-56 w-56 rounded" src="~/assets/a.jpg" /></div>
                <div><p class="mb-8">ブライダルの余興を盛り上げます。</p></div>
                <div class="flex flex-wrap content-center justify-center"><a class=" bg-blue-600 p-2 rounded text-white hover:bg-blue-400 " href="flashmob.biz">[ゼロモブ]</a></div>
              </div>
            </section>
          </div>
        </div>
      </section>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.itme{
  background-color: white;
}
</style>
