<template>
  <div>
    <main id="main">
      <my-about-section />
      <my-services-section />
      <my-counter-sectin />
      <my-portfolio-section />
      <my-testimonial-section />
      <my-blog-section />
      <my-contact-section />
    </main>
  </div>
</template>

<script>
import AboutSection from '@/components/AboutSection.vue';
import ServicesSection from '@/components/ServicesSection.vue';
import CounterSection from '@/components/CounterSection.vue';
import PortfolioSection from '@/components/PortfolioSection.vue';
import TestimonialsSection from '@/components/TestimonialsSection.vue';
import BlogSection from '@/components/BlogSection.vue';
import ContactSection from '@/components/ContactSection.vue';
export default {
  name: 'MainSection',
  data() {
    return {};
  },
  methods: {},
  components: {
    'my-about-section': AboutSection,
    'my-services-section': ServicesSection,
    'my-counter-sectin': CounterSection,
    'my-portfolio-section': PortfolioSection,
    'my-testimonial-section': TestimonialsSection,
    'my-blog-section': BlogSection,
    'my-contact-section': ContactSection
  },
  created() {},
  mounted() {}
};
</script>

<style></style>
