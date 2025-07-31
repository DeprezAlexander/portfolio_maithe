<template>
  <span class="font-black text-[12rem] leading-40">Maïthé George</span>
  <div class="flex flex-row gap-10 ml-2 font-bold mt-4">
    <a href="#portfolio" class="hover:text-blue-800">Portfolio</a>
    <a href="#about-me">About me</a>
    <a href="#contact-info">Contact info</a>
  </div>
  <section class="container mx-auto py-20">
    <WebPortfolio />
    <ContactInfo />
  </section>
</template>
<script setup lang="ts">
import WebPortfolio from './homepage/WebPortfolio.vue'
import ContactInfo from './homepage/ContactInfo.vue'
</script>
