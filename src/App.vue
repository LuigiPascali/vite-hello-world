<template>
  <div>
    <AppHero />
    <AppTitle />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
  }
};
</script>

