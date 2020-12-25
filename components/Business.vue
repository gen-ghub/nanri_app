<template>
  <section class="bg-gray-300 h-full pb-20 pt-10">
    <div class="">
      <section class="m-auto w-4/5">
        <h2 class="flex flex-wrap content-center justify-center h-40 text-2xl">
          概要＿事業内容＿タイトル
        </h2>
      </section>
      <section class="">
        <div class="grid grid-cols-3">
          <div class="flex flex-wrap content-center justify-center">
            <section>
              <div class="itme rounded bg-gray-50 p-10 ml-16 shadow-2xl">
                <div class="flex flex-wrap content-center justify-center">
                  <img class="h-56 w-56 rounded" src="~/assets/bbq1.jpg" />
                </div>
                <div>
                  <p class="mb-8">関東、関西でBBQ設備レンタルをしています。</p>
                </div>
                <div class="flex flex-wrap content-center justify-center">
                  <a
                class=" mr-5 bg-red-600 p-2 rounded text-white hover:bg-red-400"
                href="http://bbqdeli.jp/"
                >[関東]</a
              >
                  <a
                class="bg-yellow-500 p-2 rounded text-white hover:bg-yellow-300"
                href="http://www.bbq-ranger.com"
                >[関西]</a
              >
                </div>
              </div>
            </section>
          </div>
          <div class="flex flex-wrap content-center justify-center">
            <section>
              <div class="itme rounded bg-gray-50 p-10 ml-16 shadow-2xl">
                <div class="flex flex-wrap content-center justify-center">
                  <img class="h-56 w-56 rounded" src="~/assets/biru.jpg" />
                </div>
                <div>
                  <p class="mb-8">野外でビールをお楽しみ頂いております。</p>
                </div>
                <div class="flex flex-wrap content-center justify-center">
                  <a
                    class="bg-yellow-600 p-2 rounded text-white hover:bg-yellow-400"
                    href="https://beerdeli.jp/"
                    >[ビールデリ]</a
                  >
                </div>
              </div>
            </section>
          </div>
          <div class="flex flex-wrap content-center justify-center">
            <section>
              <div class="itme rounded bg-gray-50 p-10 mr-16 shadow-2xl">
                <div class="flex flex-wrap content-center justify-center">
                  <img class="h-56 w-56 rounded" src="~/assets/a.jpg" />
                </div>
                <div><p class="mb-8">ブライダルの余興を盛り上げます。</p></div>
                <div class="flex flex-wrap content-center justify-center">
                  <a
                    class="bg-blue-600 p-2 rounded text-white hover:bg-blue-400"
                    href="flashmob.biz"
                    >[ゼロモブ]</a
                  >
                </div>
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
.itme {
  background-color: white;
}
</style>
