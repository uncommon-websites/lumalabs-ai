<script lang="ts">
  // News component
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="flex justify-between items-start mb-8">
    <div>
      <h2 class="text-3xl font-medium mb-2">Recent News</h2>
      <p class="text-gray-500 text-sm max-w-xl">Stay up to date with the latest from Luma AI — company updates, model releases, and stories from across the industry.</p>
    </div>
    <button class="bg-black text-white px-5 py-2 rounded-full text-xs font-medium hover:bg-gray-800 transition-colors">All News</button>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
    <!-- Featured News (Full Width) -->
    <div class="md:col-span-3 group cursor-pointer">
      <div class="relative rounded-3xl overflow-hidden aspect-[21/9] mb-4">
        <img 
          src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?q=80&w=2072&auto=format&fit=crop" 
          alt="Luma AI Series C" 
          class="w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
        />
        <div class="absolute inset-0 bg-black/20 flex flex-col items-center justify-center text-white text-center p-6">
            <h3 class="text-4xl md:text-5xl font-bold mb-2">Luma AI</h3>
            <p class="text-3xl md:text-4xl font-bold text-white/90">$900M Series C</p>
        </div>
      </div>
      <div class="flex flex-col gap-2">
        <span class="bg-gray-100 text-gray-600 px-2 py-1 rounded text-[10px] font-medium w-fit uppercase tracking-wide">Blog Post</span>
        <h3 class="text-xl font-medium">AGI is multimodal and reality is the dataset of AGI</h3>
        <p class="text-gray-400 text-xs">November 19, 2025</p>
      </div>
    </div>

    <!-- News Item 1 -->
    <div class="group cursor-pointer">
      <div class="rounded-2xl overflow-hidden aspect-[3/2] mb-4 bg-gray-100">
        <img 
          src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=1000&auto=format&fit=crop" 
          alt="Person" 
          class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
        />
      </div>
      <div class="flex flex-col gap-2">
        <span class="bg-gray-100 text-gray-600 px-2 py-1 rounded text-[10px] font-medium w-fit uppercase tracking-wide">Press Release</span>
        <h3 class="text-base font-medium leading-snug">Luma AI Opens for International Business With Former WPP Executive Jason Day Leading New London Office</h3>
        <p class="text-gray-400 text-xs">December 2, 2025</p>
      </div>
    </div>

    <!-- News Item 2 -->
    <div class="group cursor-pointer">
      <div class="rounded-2xl overflow-hidden aspect-[3/2] mb-4 bg-gray-100 flex items-center justify-center p-8">
         <div class="flex items-center gap-2">
            <div class="font-bold text-xl">Luma AI</div>
            <div class="text-gray-300">|</div>
            <div class="font-bold text-xl">♥</div>
         </div>
      </div>
      <div class="flex flex-col gap-2">
        <span class="bg-gray-100 text-gray-600 px-2 py-1 rounded text-[10px] font-medium w-fit uppercase tracking-wide">Press Release</span>
        <h3 class="text-base font-medium leading-snug">Hartbeat and Luma AI Partner on Prompt Side Story</h3>
        <p class="text-gray-400 text-xs">October 15, 2025</p>
      </div>
    </div>

    <!-- News Item 3 -->
    <div class="group cursor-pointer">
      <div class="rounded-2xl overflow-hidden aspect-[3/2] mb-4 bg-gray-100 relative">
        <img 
          src="https://images.unsplash.com/photo-1614726365723-49cfae92782f?q=80&w=1000&auto=format&fit=crop" 
          alt="Abstract" 
          class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
        />
        <div class="absolute inset-0 flex items-center justify-center">
            <h3 class="text-white text-3xl font-bold tracking-tighter">RAY3</h3>
        </div>
      </div>
      <div class="flex flex-col gap-2">
        <span class="bg-gray-100 text-gray-600 px-2 py-1 rounded text-[10px] font-medium w-fit uppercase tracking-wide">Press Release</span>
        <h3 class="text-base font-medium leading-snug">Luma AI Launches Ray3</h3>
        <p class="text-gray-400 text-xs">September 18, 2025</p>
      </div>
    </div>

  </div>
</section>
