<template>
  <div class="flex justify-center items-center min-h-screen bg-gray-100 p-4">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="flex flex-col space-y-6">
        <div class="flex space-x-6">
          <div class="w-56 h-64">
            <Card1 />
          </div>
          <div class="w-56 h-64">
            <Card2 />
          </div>
        </div>
        <div class="w-full h-96">
          <Card3 />
        </div>
      </div>

      <div class="flex flex-col space-y-6">
        <div class="w-full h-96">
          <Card4 />
        </div>
        <div class="flex space-x-6">
          <div class="w-56 h-64">
            <Card5 />
          </div>
          <div class="w-56 h-64">
            <Card6 />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import Card1 from './components/Card1.vue';
import Card2 from './components/Card2.vue';
import Card3 from './components/Card3.vue';
import Card4 from './components/Card4.vue';
import Card5 from './components/Card5.vue';
import Card6 from './components/Card6.vue';
</script>
