<script lang="ts">
  // Hero component
</script>

<section class="relative h-screen min-h-[600px] flex flex-col justify-center items-center text-center text-white px-4 overflow-hidden bg-black">
  <!-- Background Image Placeholder -->
  <div class="absolute inset-0 z-0">
    <img 
      src="https://images.unsplash.com/photo-1574169208507-84376144848b?q=80&w=2500&auto=format&fit=crop" 
      alt="Background" 
      class="w-full h-full object-cover opacity-80"
    />
    <div class="absolute inset-0 bg-gradient-to-b from-black/30 via-transparent to-black/80"></div>
  </div>

  <div class="relative z-10 max-w-3xl w-full flex flex-col items-center gap-6 mt-20">
    <h1 class="text-5xl md:text-6xl font-medium tracking-tight">
      Make it with <br /> Dream Machine
    </h1>
    <p class="text-lg md:text-xl opacity-90 max-w-xl font-light">
      Production-ready images and videos <br /> with precision, speed, and control
    </p>

    <div class="w-full max-w-xl mt-8 relative">
      <input 
        type="text" 
        placeholder="Tell me more about your character..." 
        class="w-full h-14 pl-6 pr-12 rounded-2xl bg-white/95 text-black placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-white/50 text-sm shadow-xl"
      />
      <button aria-label="Search" class="absolute right-3 top-1/2 -translate-y-1/2 w-8 h-8 bg-black text-white rounded-full flex items-center justify-center hover:bg-gray-800 transition-colors">
        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M5 12h14M12 5l7 7-7 7"/>
        </svg>
      </button>
    </div>
  </div>
</section>
