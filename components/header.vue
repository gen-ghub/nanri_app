<template>
  <div>
    <header class="fixed">
      <div class="grid lg:grid-cols-2 ">
        <div class="text-xl lg:text-3xl ml-8"><router-link to="/">Top Page</router-link></div>
        <HeaderNav />
      </div>
    </header>
  </div>
</template>

<script>
import HeaderNav from "@/components/headerNav.vue";
export default {
  components: {
    HeaderNav
  }
};
</script>

<style lang="scss" scoped>
header{
  color: #fff;
  padding-top: 60px;
  padding-bottom: 20px;
  background-color:rgba( #000000, 0);
  width: 100%;
  
}

</style>
