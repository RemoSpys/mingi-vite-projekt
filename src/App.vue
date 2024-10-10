<template>
  <div class="flex justify-center items-center min-h-screen bg-gray-100 p-4">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <!-- Left Column -->
      <div class="flex flex-col space-y-6">
        <div class="flex space-x-6">
          <!-- Small Cards with Fixed Size -->
          <div class="w-56 h-64">
            <Card1 />
          </div>
          <div class="w-56 h-64">
            <Card2 />
          </div>
        </div>
        <!-- Larger Card with More Height -->
        <div class="w-full h-96">
          <Card3 />
        </div>
      </div>

      <!-- Right Column -->
      <div class="flex flex-col space-y-6">
        <!-- Larger Card with More Height -->
        <div class="w-full h-96">
          <Card4 />
        </div>
        <div class="flex space-x-6">
          <!-- Small Cards with Fixed Size -->
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

<script>
import Card1 from './Card1.vue';
import Card2 from './Card2.vue';
import Card3 from './Card3.vue';
import Card4 from './Card4.vue';
import Card5 from './Card5.vue';
import Card6 from './Card6.vue';

export default {
  name: 'SquareLayout',
  components: {
    Card1,
    Card2,
    Card3,
    Card4,
    Card5,
    Card6
  }
}
</script>

<style scoped>
</style>
