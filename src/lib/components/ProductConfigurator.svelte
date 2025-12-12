<script lang="ts">
  let selectedSize = '4x6';
</script>

<section class="bg-[#f9f9f7] py-24 px-6">
  <div class="max-w-[1200px] mx-auto text-center">
    <h2 class="text-[40px] font-light text-gray-900 mb-16">
      Multiple sizes. <span class="text-gray-400">Premium quality.</span>
    </h2>

    <div class="mb-8">
      <h3 class="text-2xl font-normal mb-2">Professional Photo Prints</h3>
      <p class="text-gray-500 text-sm">Museum-quality prints on premium paper.</p>
    </div>

    <!-- Print Preview -->
    <div class="relative w-full h-[400px] bg-white rounded-xl mb-8 flex items-center justify-center overflow-hidden shadow-sm">
      <div class="absolute inset-0 flex items-center justify-between px-4">
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center hover:bg-gray-200">
          <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
        </button>
      </div>
      <img src="/generated/image-beautiful-printed-photographs-laid-out-o-1765566738524-2.webp" class="h-[80%] object-contain" alt="Photo prints" />
    </div>

    <!-- Size Options -->
    <div class="flex justify-center gap-4 mb-8 flex-wrap">
      <button class="px-4 py-2 rounded-full bg-primary-100 border-2 border-primary-600 text-primary-900 text-sm font-medium">4×6</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-700 text-sm font-medium hover:bg-gray-200">5×7</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-700 text-sm font-medium hover:bg-gray-200">8×10</button>
      <button class="px-4 py-2 rounded-full bg-gray-100 text-gray-700 text-sm font-medium hover:bg-gray-200">11×14</button>
    </div>

    <div class="flex justify-center gap-8 text-sm text-gray-600 mb-4 border-b border-gray-200 pb-4 inline-flex mx-auto w-auto px-12">
      <span>Premium paper</span>
      <span>Archival quality</span>
      <span>Same-day available</span>
    </div>

    <p class="text-xs text-gray-500 mb-8">
      Starting at <span class="font-bold text-gray-900">$0.29</span> per print.<br>
      Photo Discount Membership available. ⓘ
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-6 py-3 bg-gray-100 hover:bg-gray-200 rounded-lg text-sm font-medium transition-colors text-left">
        <span class="block text-[10px] text-gray-500">Need more info?</span>
        <span class="text-primary-600">View all print options</span>
      </button>
      <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="17 8 12 3 7 8"/><line x1="12" y1="3" x2="12" y2="15"/></svg>
        Order prints online ->
      </button>
    </div>
  </div>
</section>
