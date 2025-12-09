<script lang="ts">
  // Header component
</script>

<header class="absolute top-0 left-0 w-full z-50 px-6 py-6 flex justify-between items-center text-white text-xs font-medium tracking-wide">
  <div class="flex items-center gap-2">
    <!-- Logo placeholder -->
    <div class="font-bold text-base flex items-center gap-2">
      <svg width="20" height="20" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
        <path d="M12 2L2 19H22L12 2Z" />
      </svg>
      Luma AI
    </div>
  </div>

  <nav class="hidden md:flex items-center gap-6 uppercase opacity-80">
    <a href="/" class="hover:opacity-100 transition-opacity">Dream Machine</a>
    <a href="/" class="hover:opacity-100 transition-opacity">API</a>
    <a href="/" class="hover:opacity-100 transition-opacity">Enterprise</a>
    <a href="/" class="hover:opacity-100 transition-opacity">News</a>
    <a href="/" class="hover:opacity-100 transition-opacity">Research</a>
    <a href="/" class="hover:opacity-100 transition-opacity">Community</a>
    <a href="/" class="hover:opacity-100 transition-opacity">Join Us</a>
  </nav>

  <div>
    <a href="/" class="bg-white text-black px-4 py-2 rounded-full hover:bg-gray-200 transition-colors">Sign In</a>
  </div>
</header>
