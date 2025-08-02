<template>
  <div
    class="sticky top-0 z-50 bg-white transition-all duration-100 ease-out"
    :style="{ paddingTop: headerPadding, paddingBottom: headerPadding }"
  >
    <div class="flex items-center justify-between transition-all duration-300 ease-out px-4">
      <!-- Title -->
      <span
        class="font-black transition-all duration-300 ease-out"
        :style="{
          fontSize: titleSize,
          lineHeight: titleSize,
        }"
      >
        Maïthé George
      </span>

      <!-- Navigation -->
      <div
        class="flex flex-row gap-10 font-bold transition-all duration-300 ease-out"
        :style="{
          opacity: nav2Opacity,
        }"
      >
        <a href="#portfolio" class="hover:text-blue-800 transition-colors">Portfolio</a>
        <a href="#about-me" class="hover:text-blue-800 transition-colors">About me</a>
        <a href="#contact-info" class="hover:text-blue-800 transition-colors">Contact info</a>
      </div>
    </div>
    <div
      class="flex flex-row gap-10 font-bold transition-all duration-300 ease-out ml-6"
      :style="{
        opacity: nav1Opacity,
        display: nav1Opacity === 0 ? 'none' : 'flex',
      }"
    >
      <a href="#portfolio" class="hover:text-blue-800 transition-colors">Portfolio</a>
      <a href="#about-me" class="hover:text-blue-800 transition-colors">About me</a>
      <a href="#contact-info" class="hover:text-blue-800 transition-colors">Contact info</a>
    </div>
  </div>

  <section class="container mx-auto py-20">
    <WebPortfolio />
    <!--   <ContactInfo /> -->
  </section>
</template>
<script setup lang="ts">
import { ref, computed, onMounted, onUnmounted } from 'vue'
import WebPortfolio from './homepage/WebPortfolio.vue'

const scrollY = ref(0)
const maxScroll = 300 // Maximum scroll distance for full transition
let ticking = false

const handleScroll = () => {
  if (!ticking) {
    requestAnimationFrame(() => {
      scrollY.value = window.scrollY
      ticking = false
    })
    ticking = true
  }
}

// Computed properties for smooth transitions
const scrollProgress = computed(() => {
  return Math.min(scrollY.value / maxScroll, 1)
})

const titleSize = computed(() => {
  const minSize = 2 // 2xl equivalent
  const maxSize = 12 // 12rem equivalent
  const currentSize = maxSize - (maxSize - minSize) * scrollProgress.value
  return `${currentSize}rem`
})
const headerPadding = computed(() => {
  return `${scrollProgress.value * 0.5}rem`
})

const nav1Opacity = computed(() => {
  return 1 - scrollProgress.value
})

const nav2Opacity = computed(() => {
  return scrollProgress.value
})

onMounted(() => {
  window.addEventListener('scroll', handleScroll, { passive: true })
})

onUnmounted(() => {
  window.removeEventListener('scroll', handleScroll)
})
</script>
