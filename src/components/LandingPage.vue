<template>
  <div class="bg-gray-50 text-gray-800">
    <!-- Navbar -->
    <header class="flex justify-between items-center px-8 py-4 bg-white shadow">
      <h1 class="text-2xl font-bold text-indigo-600">MyBrand</h1>
      <nav class="space-x-6 hidden md:block">
        <a href="#" class="hover:text-indigo-600">Features</a>
        <a href="#" class="hover:text-indigo-600">Pricing</a>
        <a href="#" class="hover:text-indigo-600">About</a>
        <a
          href="#"
          class="px-4 py-2 bg-indigo-600 text-white rounded-lg shadow hover:bg-indigo-700"
        >
          Get Started
        </a>
      </nav>
    </header>

    <!-- Hero Section -->
    <section
      class="text-center px-6 py-20 bg-gradient-to-r from-indigo-600 to-purple-600 text-white"
    >
      <h2 class="text-4xl md:text-6xl font-bold leading-tight">
        Sanity Integration with Vue 3
      </h2>
      <p class="mt-4 text-lg md:text-xl max-w-2xl mx-auto">
        A simple, modern landing page template built with Vue 3 and TailwindCSS.
      </p>
      <div class="mt-8 flex justify-center gap-4">
        <button
          class="px-6 py-3 bg-white text-indigo-600 font-semibold rounded-lg shadow hover:bg-gray-100"
        >
          Get Started
        </button>
        <button
          class="px-6 py-3 border border-white rounded-lg hover:bg-white/10"
        >
          Learn More
        </button>
      </div>
    </section>

    <!-- Features Section -->
    <section class="px-6 py-20">
      <h3 class="text-3xl font-bold text-center mb-12">Features</h3>
      <div class="grid md:grid-cols-3 gap-10 max-w-6xl mx-auto">
        <div class="p-6 bg-white rounded-2xl shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-3">⚡ Fast</h4>
          <p>
            Optimized Vue 3 setup and utility-first Tailwind styling for quick
            loading times.
          </p>
        </div>
        <div class="p-6 bg-white rounded-2xl shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-3">🎨 Modern UI</h4>
          <p>
            Beautiful responsive design that works across all devices
            seamlessly.
          </p>
        </div>
        <div class="p-6 bg-white rounded-2xl shadow hover:shadow-lg transition">
          <h4 class="text-xl font-semibold mb-3">🛠️ Easy to Customize</h4>
          <p>
            Well-structured components and Tailwind utilities for rapid
            development.
          </p>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section class="px-6 py-20 bg-blue-100 w-2/4 border rounded-sm mb-16 m-auto text-white text-center">
      <h3 class="text-3xl font-bold mb-4 text-black">Ready to get started?</h3>
      <p class="mb-6 text-black">
        Boost your next project with our landing page template.
      </p>
      <button
        class="px-8 py-3 bg-gray-300 text-indigo-600 font-semibold rounded-lg shadow hover:bg-gray-200"
      >
        Get Started
      </button>
    </section>

    <!-- Footer -->
    <footer class="px-6 py-8 mb-0 text-center bg-gray-100">
      <p class="text-sm text-gray-500">© 2025 MyBrand. All rights reserved.</p>
    </footer>
  </div>
</template>

<script setup>
// No extra logic for now, but Vue 3 <script setup> is ready for enhancements.
</script>

<style>
/* Optional: You can add custom styles here if needed */
</style>
