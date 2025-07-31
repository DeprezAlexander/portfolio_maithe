<template>
  <div class="max-w-4xl mx-auto">
    <!-- About Header -->
    <div class="text-center mb-16">
      <h1 class="text-4xl font-bold text-gray-900 mb-6">About This Project</h1>
      <p class="text-xl text-gray-600 leading-relaxed">
        A modern, production-ready Vue 3 application showcasing the latest web development
        practices.
      </p>
    </div>

    <!-- Tech Stack -->
    <div class="bg-white rounded-2xl shadow-lg p-8 mb-12">
      <h2 class="text-2xl font-bold text-gray-900 mb-6">Technology Stack</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="space-y-4">
          <div class="flex items-center space-x-3">
            <div class="w-8 h-8 bg-green-100 rounded-full flex items-center justify-center">
              <span class="text-green-600 font-bold text-sm">V</span>
            </div>
            <div>
              <h3 class="font-semibold text-gray-900">Vue 3</h3>
              <p class="text-gray-600 text-sm">
                Progressive JavaScript framework with Composition API
              </p>
            </div>
          </div>

          <div class="flex items-center space-x-3">
            <div class="w-8 h-8 bg-blue-100 rounded-full flex items-center justify-center">
              <span class="text-blue-600 font-bold text-sm">TS</span>
            </div>
            <div>
              <h3 class="font-semibold text-gray-900">TypeScript</h3>
              <p class="text-gray-600 text-sm">
                Type-safe JavaScript for better development experience
              </p>
            </div>
          </div>

          <div class="flex items-center space-x-3">
            <div class="w-8 h-8 bg-purple-100 rounded-full flex items-center justify-center">
              <span class="text-purple-600 font-bold text-sm">V</span>
            </div>
            <div>
              <h3 class="font-semibold text-gray-900">Vite</h3>
              <p class="text-gray-600 text-sm">Next generation frontend build tool</p>
            </div>
          </div>
        </div>

        <div class="space-y-4">
          <div class="flex items-center space-x-3">
            <div class="w-8 h-8 bg-cyan-100 rounded-full flex items-center justify-center">
              <span class="text-cyan-600 font-bold text-sm">T</span>
            </div>
            <div>
              <h3 class="font-semibold text-gray-900">Tailwind CSS</h3>
              <p class="text-gray-600 text-sm">
                Utility-first CSS framework for rapid UI development
              </p>
            </div>
          </div>

          <div class="flex items-center space-x-3">
            <div class="w-8 h-8 bg-orange-100 rounded-full flex items-center justify-center">
              <span class="text-orange-600 font-bold text-sm">P</span>
            </div>
            <div>
              <h3 class="font-semibold text-gray-900">Pinia</h3>
              <p class="text-gray-600 text-sm">State management library for Vue</p>
            </div>
          </div>

          <div class="flex items-center space-x-3">
            <div class="w-8 h-8 bg-red-100 rounded-full flex items-center justify-center">
              <span class="text-red-600 font-bold text-sm">V</span>
            </div>
            <div>
              <h3 class="font-semibold text-gray-900">Vitest</h3>
              <p class="text-gray-600 text-sm">Blazing fast unit testing framework</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Features -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
      <div class="bg-gradient-to-br from-indigo-50 to-cyan-50 rounded-xl p-6">
        <h3 class="text-xl font-bold text-gray-900 mb-4">Developer Experience</h3>
        <ul class="space-y-2 text-gray-600">
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>Hot Module Replacement</span>
          </li>
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>TypeScript Support</span>
          </li>
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>ESLint & Prettier</span>
          </li>
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>Testing Setup</span>
          </li>
        </ul>
      </div>

      <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-xl p-6">
        <h3 class="text-xl font-bold text-gray-900 mb-4">Production Ready</h3>
        <ul class="space-y-2 text-gray-600">
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>Optimized Builds</span>
          </li>
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>Code Splitting</span>
          </li>
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>Tree Shaking</span>
          </li>
          <li class="flex items-center space-x-2">
            <svg class="w-4 h-4 text-green-500" fill="currentColor" viewBox="0 0 20 20">
              <path
                fill-rule="evenodd"
                d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <span>Modern Browser Support</span>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
