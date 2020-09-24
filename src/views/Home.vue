<template>
  <div class="home">
    <header-syna />
    <banner-syna />

  </div>
</template>

<script>

// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSyna from "@/components/HeaderSyna.vue";
import BannerSyna from '@/components/BannerSyna.vue';

export default {
  name: 'Home',
  components: {
    HeaderSyna,
    BannerSyna,
  }
}
</script>
