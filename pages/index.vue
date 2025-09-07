<script setup lang="ts">
definePageMeta({
  layout: "landing"
});

useHead({
  title: 'BOT Integrated Services | One Platform, Many Solutions',
  meta: [
    {
      property: 'og:title',
      content: 'BOT Integrated Services | Travel, Real Estate, Rentals & Energy'
    },
    {
      property: 'og:description',
      content: 'Your one-stop partner for travel bookings, real estate, car rentals, and oil & gas solutions. Reliable, affordable, and customer-focused services in and out of Lagos.'
    },
    { property: 'og:image', content: '/botintegrated-og.jpg' },
    { property: 'og:image:width', content: '1200' },
    { property: 'og:image:height', content: '630' },
    {
      property: 'og:image:alt',
      content: 'BOT Integrated Services - Travel, Real Estate, Rentals & Energy'
    },
    { name: 'twitter:card', content: 'summary_large_image' },
    {
      name: 'twitter:title',
      content: 'BOT Integrated Services | Travel, Real Estate, Rentals & Energy'
    },
    {
      name: 'twitter:description',
      content: 'Trusted services for travel, property, rentals, and energy solutions. Fast, safe, and reliable support across Nigeria.'
    },
    { name: 'twitter:image', content: '/botintegrated-og.jpg' }
  ]
});


</script>

<template>
  <LandingContainer>
    <LandingHero></LandingHero>
    <LandingIntro></LandingIntro>
    <LandingServices></LandingServices>
  </LandingContainer>
  <LandingCta></LandingCta>
</template>