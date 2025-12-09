<script lang="ts">
  // Products component
</script>

<section class="py-20 px-6 max-w-7xl mx-auto">
  <div class="mb-8">
    <h2 class="text-3xl font-medium mb-2">Product & Platform</h2>
    <p class="text-gray-500 text-sm">Foundations for a new era of creativity and human expression.</p>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
    <!-- Dream Machine Card (Full Width) -->
    <div class="md:col-span-2 group relative rounded-3xl overflow-hidden bg-gray-100 min-h-[400px]">
      <img 
        src="https://images.unsplash.com/photo-1664448007546-24446f483733?q=80&w=2668&auto=format&fit=crop" 
        alt="Dream Machine" 
        class="absolute inset-0 w-full h-full object-cover transition-transform duration-700 group-hover:scale-105"
      />
      <div class="absolute bottom-0 left-0 w-full p-8 bg-gradient-to-t from-black/60 to-transparent text-white opacity-0 group-hover:opacity-100 transition-opacity">
        <!-- Optional overlay content -->
      </div>
    </div>
    
    <!-- Dream Machine Text -->
    <div class="md:col-span-2 flex justify-between items-end mb-12 mt-2">
      <div>
        <h3 class="text-xl font-medium mb-1">Dream Machine</h3>
        <p class="text-gray-500 text-sm max-w-md leading-relaxed">
            Ideate, visualize, and create videos using our most powerful image and video models. Available now on iOS and the Web.
        </p>
      </div>
      <div class="flex gap-3">
         <button class="bg-black text-white px-5 py-2 rounded-full text-xs font-medium hover:bg-gray-800 transition-colors">Try now</button>
         <button class="bg-gray-100 text-black px-5 py-2 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Learn more</button>
      </div>
    </div>

    <!-- Models Card -->
    <div class="flex flex-col gap-4">
      <div class="bg-gray-100 rounded-3xl aspect-[4/3] relative overflow-hidden flex items-center justify-center p-8">
         <!-- Mockup of Models UI -->
         <div class="bg-black/90 text-white p-6 rounded-xl w-full max-w-xs shadow-2xl backdrop-blur-sm border border-white/10">
            <div class="text-[10px] text-gray-500 mb-3 uppercase tracking-wider font-semibold">Models</div>
            <div class="space-y-4">
                <div class="border-l-2 border-white pl-3 py-1">
                    <div class="text-xs font-semibold text-white">Ray3 Reasoning</div>
                    <div class="text-[10px] text-gray-400 mt-0.5">Visual reasoning for complex tasks</div>
                </div>
                <div class="pl-3 py-1 opacity-60 hover:opacity-100 transition-opacity cursor-pointer">
                    <div class="text-xs font-semibold text-white">Ray3</div>
                    <div class="text-[10px] text-gray-400 mt-0.5">Aesthetic quality and high motion</div>
                </div>
                 <div class="pl-3 py-1 opacity-40">
                    <div class="text-[10px] text-gray-500 uppercase mb-1">Legacy Models</div>
                    <div class="text-xs font-semibold text-white">Ray2</div>
                    <div class="text-[10px] text-gray-400 mt-0.5">No Queue</div>
                </div>
            </div>
         </div>
      </div>
      <div class="flex flex-col gap-2">
        <h3 class="text-xl font-medium">Models</h3>
        <p class="text-gray-500 text-sm leading-relaxed">State-of-the-art multimodal models that power Dream Machine and enable high-fidelity image and video.</p>
        <div class="mt-2">
            <button class="bg-black text-white px-5 py-2 rounded-full text-xs font-medium hover:bg-gray-800 transition-colors">Learn more</button>
        </div>
      </div>
    </div>

    <!-- Luma AI API Card -->
    <div class="flex flex-col gap-4">
      <div class="bg-gray-100 rounded-3xl aspect-[4/3] relative overflow-hidden flex items-center justify-center p-8">
         <!-- Mockup of API Code -->
         <div class="bg-black text-gray-300 font-mono text-[10px] md:text-xs p-6 rounded-xl w-full max-w-xs shadow-2xl overflow-hidden leading-relaxed">
            <div class="text-gray-500 mb-2"># Generate video</div>
            <div class="text-white"><span class="text-purple-400">gen</span> = <span class="text-blue-400">create</span>(&#123;</div>
            <div class="pl-4"><span class="text-orange-300">prompt</span>: <span class="text-green-400">"insane camera fly through mount Everest"</span>,</div>
            <div class="pl-4"><span class="text-orange-300">aspect_ratio</span>: <span class="text-green-400">"16:9"</span>,</div>
            <div class="text-white">&#125;);</div>
         </div>
      </div>
      <div class="flex flex-col gap-2">
        <h3 class="text-xl font-medium">Luma AI API</h3>
        <p class="text-gray-500 text-sm leading-relaxed">Build and scale creative products with high-quality video and image generation models through the Luma API.</p>
        <div class="mt-2">
            <button class="bg-black text-white px-5 py-2 rounded-full text-xs font-medium hover:bg-gray-800 transition-colors">Start building</button>
        </div>
      </div>
    </div>

  </div>
</section>
