<template>
  <div class="min-h-screen">
    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-[#12b488] to-[#0ea571] text-white py-20">
      <div class="container mx-auto px-4 text-center">
        <h1 class="text-5xl font-bold mb-6">Welcome to Nuxt Shop</h1>
        <p class="text-xl mb-8 max-w-2xl mx-auto">
          Discover amazing products at unbeatable prices. Your one-stop destination for quality shopping.
        </p>
        <button class="btn text-lg px-8 py-3 bg-white text-[#12b488] hover:bg-gray-100 transition-colors">
          Shop Now
        </button>
      </div>
    </section>

    <!-- Features Section -->
    <section class="py-16">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Why Choose Us?</h2>
        <div class="grid md:grid-cols-3 gap-8">
          <div class="card text-center">
            <div class="w-16 h-16 bg-[#12b488] rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3 text-gray-800">Best Prices</h3>
            <p class="text-gray-600">Competitive pricing on all our products with regular discounts and special offers.</p>
          </div>
          
          <div class="card text-center">
            <div class="w-16 h-16 bg-[#12b488] rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10M4 7v10l8 4"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3 text-gray-800">Fast Delivery</h3>
            <p class="text-gray-600">Quick and reliable shipping to get your orders to you as fast as possible.</p>
          </div>
          
          <div class="card text-center">
            <div class="w-16 h-16 bg-[#12b488] rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold mb-3 text-gray-800">Quality Guaranteed</h3>
            <p class="text-gray-600">All products are carefully selected and tested to ensure the highest quality standards.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Featured Products Section -->
    <section class="py-16 bg-gray-100">
      <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Featured Products</h2>
        <div class="grid md:grid-cols-4 gap-6">
          <div class="card">
            <div class="h-48 bg-gray-200 rounded-md mb-4 flex items-center justify-center">
              <span class="text-gray-500">Product Image</span>
            </div>
            <h3 class="font-semibold mb-2">Premium Headphones</h3>
            <p class="text-[#12b488] font-bold text-lg">$99.99</p>
            <button class="btn w-full mt-3">Add to Cart</button>
          </div>
          
          <div class="card">
            <div class="h-48 bg-gray-200 rounded-md mb-4 flex items-center justify-center">
              <span class="text-gray-500">Product Image</span>
            </div>
            <h3 class="font-semibold mb-2">Smart Watch</h3>
            <p class="text-[#12b488] font-bold text-lg">$199.99</p>
            <button class="btn w-full mt-3">Add to Cart</button>
          </div>
          
          <div class="card">
            <div class="h-48 bg-gray-200 rounded-md mb-4 flex items-center justify-center">
              <span class="text-gray-500">Product Image</span>
            </div>
            <h3 class="font-semibold mb-2">Wireless Speaker</h3>
            <p class="text-[#12b488] font-bold text-lg">$79.99</p>
            <button class="btn w-full mt-3">Add to Cart</button>
          </div>
          
          <div class="card">
            <div class="h-48 bg-gray-200 rounded-md mb-4 flex items-center justify-center">
              <span class="text-gray-500">Product Image</span>
            </div>
            <h3 class="font-semibold mb-2">Phone Case</h3>
            <p class="text-[#12b488] font-bold text-lg">$24.99</p>
            <button class="btn w-full mt-3">Add to Cart</button>
          </div>
        </div>
      </div>
    </section>

    <!-- Newsletter Section -->
    <section class="py-16 bg-[#12b488] text-white">
      <div class="container mx-auto px-4 text-center">
        <h2 class="text-3xl font-bold mb-4">Stay Updated</h2>
        <p class="text-lg mb-8">Subscribe to our newsletter for the latest deals and product updates.</p>
        <div class="max-w-md mx-auto flex gap-4">
          <input 
            type="email" 
            placeholder="Enter your email" 
            class="flex-1 px-4 py-2 rounded-md text-gray-800"
          >
          <button class="btn bg-white text-[#12b488] hover:bg-gray-100">Subscribe</button>
        </div>
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