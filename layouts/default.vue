<template>
  <div>
    <TheHeader/>
    <div class="container">
        <nuxt />
    </div>
  </div>
</template>

<script>
import TheHeader from '~/components/TheHeader.vue';
export default {
    components: {
        TheHeader,
    },
};
</script>

<style>
@import '~/assets/sass/main.scss';
</style>
