<script lang="ts">
  const images = [
    "/generated/image-elegant-renovated-boston-brownstone-exte-1765581182114-0.webp",
    "/generated/image-luxury-modern-apartment-interior-in-bost-1765581184545-1.webp",
    "/generated/image-renovated-luxury-apartment-building-exte-1765581195009-6.webp"
  ];
</script>

<section class="bg-white pb-24 overflow-hidden" id="projects">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each images as img}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={img} alt="OnPoint development project" class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Recent Projects <span class="text-gray-400">Boston & Greater New England</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
