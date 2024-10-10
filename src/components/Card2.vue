<template>
  <div class="bg-green-600 text-white rounded-2xl shadow-xl p-2 md:p-4 flex flex-col justify-between w-full h-full relative overflow-hidden">
    <svg class="absolute inset-0 w-full h-full" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 400 400" opacity="0.1">
      <defs>
        <pattern id="lines" x="0" y="0" width="10" height="10" patternUnits="userSpaceOnUse">
          <rect x="0" y="0" width="2" height="10" fill="white" />
        </pattern>
      </defs>
      <rect width="100%" height="100%" fill="url(#lines)" />
    </svg>
    <div class="bg-white text-xs text-green-600 font-bold px-1 py-1 rounded-full self-start z-10">
      Organizational
    </div>
    <div class="flex flex-col items-start mt-auto mb-2 z-10">
      <h2 class="text-lg md:text-2xl font-bold mb-1">Growth</h2>
      <p class="text-xs md:text-sm">
        Create a development plan that best fits your goals and sense of purpose.
      </p>
    </div>
    <div class="flex items-center space-x-2 text-white text-sm z-10">
      <div class="flex items-center space-x-1">
        <i class="fas fa-star"></i> <span>4.6</span>
      </div>
      <div class="flex items-center space-x-1">
        <i class="fas fa-check-circle"></i> <span>100%</span>
      </div>
    </div>
  </div>
</template>

<script setup>
</script>
