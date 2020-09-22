<template>
  <div class="home">
    <header-syna></header-syna>
  </div>
</template>

<script>

// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderSyna from "@/components/HeaderSyna.vue";

export default {
  name: 'Home',
  components: {
    HeaderSyna,
  }
}
</script>
