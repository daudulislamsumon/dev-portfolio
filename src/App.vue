<template>
  <div id="app">
    <div id="page-top">
      <my-header />
      <my-intro-section />
      <my-main-section />
      <my-footer />
      <router-view />
    </div>
  </div>
</template>
<script>
import Header from '@/components/includes/Header.vue';
import IntroSection from '@/views/IntroSection.vue';
import MainSection from '@/views/MainSection.vue';
import Footer from '@/components/includes/Footer.vue';
export default {
  name: 'app',
  data() {
    return {};
  },
  methods: {},
  components: {
    'my-header': Header,
    'my-intro-section': IntroSection,
    'my-main-section': MainSection,
    'my-footer': Footer
  },
  created() {},
  mounted() {}
};
</script>
<style></style>
