<script>
  // Import icons - we'll use simple SVGs for now since lucide-react isn't available
</script>

<div class="min-h-screen bg-[#0E0F11] text-white overflow-hidden relative">
  <div class="relative z-10 min-h-screen flex flex-col items-center justify-center px-4 sm:px-6 lg:px-8">
    <!-- Main content -->
    <div class="flex flex-col lg:flex-row items-center justify-center gap-8 lg:gap-20 max-w-6xl mx-auto">
      <!-- Avatar -->
      <div class="relative w-50 h-50 flex items-center justify-center">
        <!-- Glow/blur behind the image -->
        <div class="absolute inset-0 flex items-center justify-center">
          <div class="w-50 h-50 bg-[#E86C3F] opacity-25 rounded-full blur-3xl z-0"></div>
        </div>
        <!-- Avatar image -->
        <div class="w-50 h-50">
          <img
            src="/img.webp"
            alt="Profile"
            class="w-full h-full rounded-full object-cover shadow-lg"
          />
        </div>
      </div>
      
      <!-- Content -->
      <div class="text-center lg:text-left space-y-6 max-w-2xl">
        <!-- Title -->
        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-bold font-mono">
          {"{orynx}"}
        </h1>
        
        <!-- Subtext -->
        <div class="text-lg sm:text-xl lg:text-2xl font-mono opacity-60 space-y-2">
          <p>Builder of thoughts, breaker of patterns.</p>
          <p>This is just a terminal window into the void.<span class="blink">_</span></p>
        </div>
        
        <!-- Social buttons -->
        <div class="flex flex-row gap-14 justify-center lg:justify-start pt-6">
          <!-- Github icon -->
          <a href="https://github.com/OrynVail" class="opacity-60 hover:opacity-100 transition" aria-label="Github">
            <svg class="w-8 h-8" viewBox="0 0 24 24" fill="currentColor">
              <path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/>
            </svg>
          </a>
          <!-- X icon -->
          <a href="https://x.com/MindofOryn" class="opacity-60 hover:opacity-100 transition" aria-label="X">
            <svg class="w-8 h-8" viewBox="0 0 24 24" fill="currentColor">
              <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
            </svg>
          </a>
          <!-- Mail icon -->
          <a href="mailto:vail@orynx.space" class="opacity-60 hover:opacity-100 transition" aria-label="Mail">
            <svg class="w-8 h-8" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
              <rect width="20" height="16" x="2" y="4" rx="2"/>
              <path d="m22 7-10 5L2 7"/>
            </svg>
          </a>
        </div>
      </div>
    </div>
    
    <!-- Footer -->
    <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2">
      <p class="text-sm font-mono opacity-80 text-center">
        © 2025 — Built in Silence. Powered by Entropy.
      </p>
    </div>
  </div>
</div>

<style>
  .blink {
    animation: blink 1s steps(2, start) infinite;
  }
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }
</style>
