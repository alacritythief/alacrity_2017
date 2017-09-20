<template>
  <div class="wrapper">
    <TopHeader/>
    <nuxt/>
  </div>
</template>

<script>
import TopHeader from '~/components/Header.vue'

export default {
  components: {
    TopHeader
  }
}
</script>
