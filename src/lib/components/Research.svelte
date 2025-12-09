<script lang="ts">
  // Research component
</script>

<section class="bg-[#050505] text-white py-24 px-6">
  <div class="max-w-7xl mx-auto">
    <div class="mb-16">
      <h2 class="text-3xl font-medium mb-2">Research</h2>
      <p class="text-gray-400 text-sm max-w-xl">We are focused on foundational research and systems engineering to build multimodal general intelligence.</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-16">
        <!-- RAY3 Large Card -->
        <div class="md:col-span-2 relative rounded-3xl overflow-hidden bg-gray-900 aspect-[21/9] group">
            <!-- Placeholder for RAY3 visual -->
             <div class="absolute inset-0 bg-gradient-to-r from-gray-900 to-gray-800"></div>
             <div class="absolute top-8 left-8 flex items-center gap-2">
                <h3 class="text-2xl font-bold">RAY3</h3>
                <span class="bg-white/10 text-white px-2 py-0.5 rounded text-[10px] font-medium border border-white/20">NEW</span>
             </div>
             <div class="absolute top-8 right-8">
                <button class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Discover</button>
             </div>
             <div class="absolute bottom-8 left-8 max-w-lg">
                <p class="text-gray-400 text-sm">World's first reasoning video model. World's first HDR model. A model designed to tell stories.</p>
             </div>
        </div>

        <!-- RAY2 Card -->
        <div class="flex flex-col gap-4">
            <div class="rounded-3xl overflow-hidden aspect-video relative group bg-gray-800">
                <img 
                  src="https://images.unsplash.com/photo-1635070041078-e363dbe005cb?q=80&w=2070&auto=format&fit=crop" 
                  alt="Alien" 
                  class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105"
                />
            </div>
            <div>
                <h3 class="text-xl font-bold mb-2">RAY2</h3>
                <p class="text-gray-400 text-xs mb-4 leading-relaxed h-10">A new generation of video model capable of producing fast coherent motion, ultra-realistic details, and logical event sequences.</p>
                <button class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Discover</button>
            </div>
        </div>

        <!-- PHOTON Card -->
        <div class="flex flex-col gap-4">
            <div class="rounded-3xl overflow-hidden aspect-video relative group bg-gray-800 p-6 flex items-center justify-center">
                <div class="relative w-full h-full">
                     <img 
                        src="https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?q=80&w=2564&auto=format&fit=crop" 
                        alt="Photon" 
                        class="w-full h-full object-cover rounded-xl shadow-lg"
                     />
                     <!-- Overlay UI elements to mimic the screenshot -->
                     <div class="absolute top-4 left-4 w-1/3 h-1/3 bg-white/10 backdrop-blur-md rounded-lg border border-white/20"></div>
                </div>
            </div>
            <div>
                <h3 class="text-xl font-bold mb-2">PHOTON</h3>
                <p class="text-gray-400 text-xs mb-4 leading-relaxed h-10">Creative, intelligent and personalizable image-generation model that delivers ultra high quality and 10s higher cost efficiency.</p>
                <button class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Discover</button>
            </div>
        </div>
    </div>

    <!-- Text Heavy Cards Row -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mb-16">
        <div class="bg-transparent border-t border-gray-800 pt-6">
            <h3 class="text-lg font-bold mb-2 leading-tight">Pushing the Limit of Efficient Inference-Time Scaling with Terminal Velocity Matching</h3>
            <div class="text-gray-500 text-xs mb-4">
                <p>November 26, 2025</p>
                <p>Linqi Zhou, Ayaan Haque</p>
            </div>
            <button class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Read More</button>
        </div>

        <div class="bg-transparent border-t border-gray-800 pt-6">
            <h3 class="text-lg font-bold mb-2 leading-tight">Ray3 Evaluation Report – State-of-the-Art Performance for Pro Video Generation</h3>
            <div class="text-gray-500 text-xs mb-4">
                <p>October 14, 2025</p>
                <p>Sabrina Day, Simran Motwani</p>
            </div>
            <button class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Read More</button>
        </div>
    </div>

    <!-- Image Grid Card -->
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="flex flex-col gap-4">
             <div class="grid grid-cols-3 gap-1 rounded-3xl overflow-hidden">
                <img src="https://images.unsplash.com/photo-1543466835-00a7907e9de1?q=80&w=1000&auto=format&fit=crop" class="w-full h-24 object-cover" alt="Dog"/>
                <img src="https://images.unsplash.com/photo-1517849845537-4d257902454a?q=80&w=1000&auto=format&fit=crop" class="w-full h-24 object-cover" alt="Dog"/>
                <img src="https://images.unsplash.com/photo-1583511655857-d19b40a7a54e?q=80&w=1000&auto=format&fit=crop" class="w-full h-24 object-cover" alt="Dog"/>
                <img src="https://images.unsplash.com/photo-1583337130417-3346a1be7dee?q=80&w=1000&auto=format&fit=crop" class="w-full h-24 object-cover" alt="Dog"/>
                <img src="https://images.unsplash.com/photo-1537151608828-ea2b11777ee8?q=80&w=1000&auto=format&fit=crop" class="w-full h-24 object-cover" alt="Dog"/>
                <img src="https://images.unsplash.com/photo-1518020382113-a7e8fc38eac9?q=80&w=1000&auto=format&fit=crop" class="w-full h-24 object-cover" alt="Dog"/>
             </div>
             <div class="mt-2">
                <h3 class="text-lg font-bold mb-2 leading-tight">Breaking the Algorithmic Ceiling in Pre-Training with Inductive Moment Matching</h3>
                <div class="text-gray-500 text-xs mb-4">
                    <p>March 11, 2025</p>
                    <p>Linqi Zhou, Jiaming Song</p>
                </div>
                <button class="bg-white text-black px-4 py-1.5 rounded-full text-xs font-medium hover:bg-gray-200 transition-colors">Read More</button>
             </div>
        </div>
    </div>

  </div>
</section>
