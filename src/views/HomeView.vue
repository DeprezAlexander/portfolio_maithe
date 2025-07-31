<script setup lang="ts">
// We can keep the welcome component or create new content
</script>

<template>
  <div class="space-y-16">
    <!-- Hero Section -->
    <section class="text-center py-20">
      <h2 class="text-5xl font-bold text-gray-900 mb-6">
        Build Something
        <span class="bg-gradient-to-r from-purple-600 to-pink-600 bg-clip-text text-transparent">
          Amazing
        </span>
      </h2>
      <p class="text-xl text-gray-600 max-w-2xl mx-auto mb-8">
        Start your next project with this modern Vue 3 + Tailwind CSS template. Fast, flexible, and
        beautiful by default.
      </p>
      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <button
          class="bg-indigo-600 hover:bg-indigo-700 text-white font-semibold py-3 px-8 rounded-lg transition-colors duration-200"
        >
          Get Started
        </button>
        <button
          class="border border-gray-300 hover:border-gray-400 text-gray-700 font-semibold py-3 px-8 rounded-lg transition-colors duration-200"
        >
          Learn More
        </button>
      </div>
    </section>

    <!-- Features Grid -->
    <section class="py-16">
      <h3 class="text-3xl font-bold text-center text-gray-900 mb-12">Why Choose This Stack?</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
        <div class="text-center">
          <div
            class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4"
          >
            <svg
              class="w-8 h-8 text-green-600"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M13 10V3L4 14h7v7l9-11h-7z"
              ></path>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-gray-900 mb-2">Fast Development</h4>
          <p class="text-gray-600 text-sm">Hot reload and instant feedback for rapid iteration.</p>
        </div>

        <div class="text-center">
          <div
            class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4"
          >
            <svg
              class="w-8 h-8 text-blue-600"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4"
              ></path>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-gray-900 mb-2">Highly Customizable</h4>
          <p class="text-gray-600 text-sm">
            Tailwind's utility classes make styling flexible and maintainable.
          </p>
        </div>

        <div class="text-center">
          <div
            class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4"
          >
            <svg
              class="w-8 h-8 text-purple-600"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
              ></path>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-gray-900 mb-2">Type Safe</h4>
          <p class="text-gray-600 text-sm">
            Full TypeScript support for better development experience.
          </p>
        </div>

        <div class="text-center">
          <div
            class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mx-auto mb-4"
          >
            <svg
              class="w-8 h-8 text-orange-600"
              fill="none"
              stroke="currentColor"
              viewBox="0 0 24 24"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"
              ></path>
            </svg>
          </div>
          <h4 class="text-lg font-semibold text-gray-900 mb-2">Production Ready</h4>
          <p class="text-gray-600 text-sm">Optimized builds and modern tooling for deployment.</p>
        </div>
      </div>
    </section>
  </div>
</template>
