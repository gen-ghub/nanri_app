<template>
  <div>
    <header>
      <router-link to="/">Top Page</router-link>
      <HeaderNav />
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
  padding: 20px;
  background-color: #022444;
}
</style>
