<script setup>
import pageData from '@/data/index.json'
const page = ref(pageData)

definePageMeta({
  layout: "default",
});
</script>

<template>
  <Container>
    <Hero
      :title="BIT OF EVERYTHING"
      :description="BIT OF EVERYTHING"
      :image=
      :imageAlt
      :buttons=
    ></Hero>
    <Logos :title="page.logos.title" :icons="page.logos.icons"></Logos>
    <Features
      :title="BIT OF EVERYTHING"
      :description="BIT OF EVERYTHING"
      :items=
    ></Features>
    <Testimonials
      :title="BIT OF EVERYTHING"
      :description="BIT OF EVERYTHING"
      :items=
    ></Testimonials>
    <Cta
      :title="BIT OF EVERYTHING"
      :description="BIT OF EVERYTHING"
      :buttons="BOE.COM.PK"
    ></Cta>
  </Container>
</template>
