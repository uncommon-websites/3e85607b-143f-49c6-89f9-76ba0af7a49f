<div class="relative bg-black rounded-[3rem] p-3 w-full h-full shadow-2xl ring-1 ring-gray-900/5">
  <!-- Power Button -->
  <div class="absolute -right-[2px] top-24 w-[2px] h-12 bg-gray-800 rounded-r-md"></div>
  <!-- Volume Buttons -->
  <div class="absolute -left-[2px] top-24 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>
  <div class="absolute -left-[2px] top-36 w-[2px] h-8 bg-gray-800 rounded-l-md"></div>

  <!-- Screen -->
  <div class="bg-white w-full h-full rounded-[2.5rem] overflow-hidden relative flex flex-col">
    <!-- Status Bar / Notch Area -->
    <div class="h-12 w-full flex justify-center items-start pt-2 absolute top-0 left-0 z-20">
      <div class="w-28 h-7 bg-black rounded-full flex items-center justify-center gap-2 px-3">
        <!-- Dynamic Island Content Simulation -->
        <div class="w-full h-full flex items-center justify-between opacity-0">
           <!-- Hidden content just to keep size -->
        </div>
      </div>
    </div>

    <!-- App Content -->
    <div class="flex-1 overflow-y-auto pt-12 px-6 pb-6 text-xs font-medium select-none scrollbar-hide">
      <!-- Header -->
      <div class="flex justify-between items-center mb-6 mt-2">
        <h2 class="text-2xl font-bold tracking-tight">Nearby Mosques</h2>
        <div class="text-[10px] text-gray-400 font-semibold uppercase tracking-wide">
          Leicester
        </div>
      </div>

      <!-- Prayer Times Card -->
      <div class="mb-6 p-4 bg-gradient-to-br from-primary-50 to-primary-100 rounded-2xl border border-primary-200">
        <div class="text-[10px] text-primary-700 font-bold uppercase tracking-wide mb-3">Today's Prayer Times</div>
        <div class="grid grid-cols-3 gap-3 text-[11px]">
          <div class="flex flex-col">
            <span class="text-gray-500 text-[9px] mb-1">Fajr</span>
            <span class="font-bold text-black">05:42</span>
          </div>
          <div class="flex flex-col">
            <span class="text-gray-500 text-[9px] mb-1">Dhuhr</span>
            <span class="font-bold text-black">12:15</span>
          </div>
          <div class="flex flex-col">
            <span class="text-gray-500 text-[9px] mb-1">Asr</span>
            <span class="font-bold text-black">14:32</span>
          </div>
          <div class="flex flex-col">
            <span class="text-gray-500 text-[9px] mb-1">Maghrib</span>
            <span class="font-bold text-primary-600">16:48</span>
          </div>
          <div class="flex flex-col">
            <span class="text-gray-500 text-[9px] mb-1">Isha</span>
            <span class="font-bold text-black">18:30</span>
          </div>
        </div>
      </div>

      <!-- Mosque List -->
      <div class="space-y-4">
        <!-- Mosque 1 -->
        <div class="flex gap-3 p-3 bg-white rounded-xl border border-gray-100 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-primary-100 flex items-center justify-center flex-shrink-0">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M12 3C8 3 6 5 6 7h12c0-2-2-4-6-4z"/>
              <rect x="7" y="7" width="10" height="10" rx="1"/>
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="font-bold text-sm mb-0.5">Leicester Central Mosque</div>
            <div class="text-[10px] text-gray-500 mb-1.5">0.3 mi • Conduit Street</div>
            <div class="text-[9px] text-primary-600 font-semibold">Next: Maghrib 16:48</div>
          </div>
        </div>

        <!-- Mosque 2 -->
        <div class="flex gap-3 p-3 bg-white rounded-xl border border-gray-100 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-primary-100 flex items-center justify-center flex-shrink-0">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M12 3C8 3 6 5 6 7h12c0-2-2-4-6-4z"/>
              <rect x="7" y="7" width="10" height="10" rx="1"/>
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="font-bold text-sm mb-0.5">Masjid Umar</div>
            <div class="text-[10px] text-gray-500 mb-1.5">0.7 mi • Evington Road</div>
            <div class="text-[9px] text-gray-400 font-semibold">Next: Maghrib 16:50</div>
          </div>
        </div>

        <!-- Mosque 3 -->
        <div class="flex gap-3 p-3 bg-white rounded-xl border border-gray-100 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-primary-100 flex items-center justify-center flex-shrink-0">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M12 3C8 3 6 5 6 7h12c0-2-2-4-6-4z"/>
              <rect x="7" y="7" width="10" height="10" rx="1"/>
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="font-bold text-sm mb-0.5">Jame Masjid</div>
            <div class="text-[10px] text-gray-500 mb-1.5">1.2 mi • Belgrave Road</div>
            <div class="text-[9px] text-gray-400 font-semibold">Next: Maghrib 16:48</div>
          </div>
        </div>

        <!-- Mosque 4 -->
        <div class="flex gap-3 p-3 bg-white rounded-xl border border-gray-100 shadow-sm">
          <div class="w-10 h-10 rounded-lg bg-primary-100 flex items-center justify-center flex-shrink-0">
            <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
              <path d="M12 3C8 3 6 5 6 7h12c0-2-2-4-6-4z"/>
              <rect x="7" y="7" width="10" height="10" rx="1"/>
            </svg>
          </div>
          <div class="flex-1 min-w-0">
            <div class="font-bold text-sm mb-0.5">Al-Aqsa Mosque</div>
            <div class="text-[10px] text-gray-500 mb-1.5">1.5 mi • Spinney Hill</div>
            <div class="text-[9px] text-gray-400 font-semibold">Next: Maghrib 16:48</div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Home Indicator -->
    <div class="absolute bottom-1 left-1/2 -translate-x-1/2 w-32 h-1 bg-black rounded-full opacity-20"></div>
  </div>
</div>

