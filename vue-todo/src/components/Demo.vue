<template>
  <div id="root">
    <p>{{ originalPrice }}</p>
    <p>{{ doublePrice }}</p>
    <p>{{ triplePrice }}</p>
  </div>
</template>

<script>
import { mapGetters } from 'vuex';

export default {
  computed: {
    ...mapGetters(['originalPrice', 'doublePrice', 'triplePrice']),
    
    // originalPrice() {
    //   return this.$store.gettes.originalPrice;
    // },
    // doublePrice() {
    //   return this.$store.gettes.doublePrice;
    // },
    // triplePrice() {
    //   return this.$store.gettes.triplePrice;
    // }
  }
}
</script>

<style>

</style>