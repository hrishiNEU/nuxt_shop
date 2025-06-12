<template>
  <div class="min-h-screen">
    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-[#12b488] to-[#0ea571] text-white py-20">
      <div class="container mx-auto px-4 text-center">
        <h1 class="text-5xl font-bold mb-6">About Nuxt Shop</h1>
        <p class="text-xl max-w-2xl mx-auto">
          Learn more about our story, mission, and commitment to providing exceptional shopping experiences.
        </p>
      </div>
    </section>

    <!-- Our Story Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <div class="max-w-4xl mx-auto">
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <div>
              <h2 class="text-3xl font-bold mb-6 text-gray-800">Our Story</h2>
              <p class="text-gray-600 mb-4">
                Founded in 2020, Nuxt Shop began as a small startup with a big vision: to make quality products accessible to everyone at affordable prices. What started in a garage has grown into a trusted e-commerce platform serving thousands of customers worldwide.
              </p>
              <p class="text-gray-600">
                We believe that great shopping experiences shouldn't be complicated. That's why we've built our platform around simplicity, quality, and customer satisfaction.
              </p>
            </div>
            <div class="card">
              <div class="h-64 bg-gray-200 rounded-md flex items-center justify-center">
                <span class="text-gray-500">Company Image</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Mission & Values Section -->
    <section class="py-16 bg-gray-100">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Our Mission & Values</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="card text-center">
            <div class="w-16 h-16 bg-[#12b488] rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3 text-gray-800">Customer First</h3>
            <p class="text-gray-600">Every decision we make is centered around providing the best possible experience for our customers.</p>
          </div>
          
          <div class="card text-center">
            <div class="w-16 h-16 bg-[#12b488] rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3 text-gray-800">Innovation</h3>
            <p class="text-gray-600">We continuously evolve our platform and services to stay ahead of the curve and meet changing needs.</p>
          </div>
          
          <div class="card text-center">
            <div class="w-16 h-16 bg-[#12b488] rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3 text-gray-800">Trust & Security</h3>
            <p class="text-gray-600">We prioritize the security of your data and transactions, ensuring a safe shopping environment.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-[#12b488] text-white">
      <div class="container mx-auto px-4">
        <div class="grid md:grid-cols-4 gap-8 text-center">
          <div>
            <div class="text-4xl font-bold mb-2">10K+</div>
            <div class="text-lg">Happy Customers</div>
          </div>
          <div>
            <div class="text-4xl font-bold mb-2">5K+</div>
            <div class="text-lg">Products</div>
          </div>
          <div>
            <div class="text-4xl font-bold mb-2">50+</div>
            <div class="text-lg">Countries Served</div>
          </div>
          <div>
            <div class="text-4xl font-bold mb-2">99.9%</div>
            <div class="text-lg">Uptime</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section class="py-16">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold mb-6 text-gray-800">Get In Touch</h2>
        <p class="text-gray-600 mb-8 max-w-2xl mx-auto">
          Have questions or want to learn more about Nuxt Shop? We'd love to hear from you.
        </p>
        <button class="btn text-lg px-8 py-3">Contact Us</button>
      </div>
    </section>
  </div>
</template>

<script setup>
// You can add any page-specific logic here
</script>

<style scoped>
/* Any additional custom styles can go here */
</style>
