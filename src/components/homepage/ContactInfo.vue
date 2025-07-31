<template>
  <div id="contact-info" class="bg-black flex flex-col gap-3 text-white text-4xl font-black">
    <a href="mailto:maithe.george@icloud.com" class="flex w-fit hover:underline items-center gap-2">
      <EnvelopeIcon class="h-8 w-8" />
      maithe.george@icloud.com
    </a>
    <a href="tel:+32495616240" class="flex w-fit hover:underline items-center gap-2">
      <PhoneIcon class="h-8 w-8" />
      +32495616240
    </a>
    <a
      href="https://www.instagram.com/maithegeorge"
      class="flex items-center gap-2 w-fit hover:underline"
    >
      <font-awesome-icon :icon="['fab', 'instagram']" class="h-8 w-8" />
      maithegeorge
    </a>
  </div>
</template>
<script setup lang="ts">
import { PhoneIcon, EnvelopeIcon } from '@heroicons/vue/24/solid'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { library } from '@fortawesome/fontawesome-svg-core'
import { faInstagram } from '@fortawesome/free-brands-svg-icons'

// Add Instagram icon to the library
library.add(faInstagram)
</script>
