<template>
  <Container>
    <!-- Hero Section -->
    <Hero
      :title="page.hero.title"
      :description="page.hero.description"
      :image="page.hero.image"
      :imageAlt="page.hero.imageAlt"
      :buttons="page.hero.buttons"
    ></Hero>

    <!-- REMOVE Logos Section -->
    <!-- <Logos 
      :title="page.logos.title" 
      :icons="page.logos.icons" 
    ></Logos> -->

    <!-- Features Section -->
    <Features
      :title="page.features.title"
      :description="page.features.description"
      :items="page.features.items"
    ></Features>

    <!-- Testimonials Section -->
    <Testimonials
      :title="page.testimonials.title"
      :description="page.testimonials.description"
      :items="page.testimonials.items"
    ></Testimonials>

    <!-- Call to Action Section -->
    <Cta
      :title="page.cta.title"
      :description="page.cta.description"
      :buttons="page.cta.buttons"
    ></Cta>
  </Container>
</template>

