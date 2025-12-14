<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Button from '$lib/components/Button.svelte';
  import Apple from '$lib/components/icons/Apple.svelte';
  import MosqueIcon from '$lib/components/icons/MosqueIcon.svelte';
  import ClockIcon from '$lib/components/icons/ClockIcon.svelte';
  import LocationIcon from '$lib/components/icons/LocationIcon.svelte';
  import PhoneUI from '$lib/components/PhoneUI.svelte';
</script>

<div class="min-h-screen bg-white text-black font-sans selection:bg-gray-200">
  <Header />

  <main class="flex flex-col items-center w-full">
    <!-- Hero Section -->
    <section class="flex flex-col items-center text-center pt-10 pb-12 px-4 max-w-4xl mx-auto">
      <h2 class="text-sm font-semibold mb-6 text-primary-600">Unity Hub</h2>
      
      <h1 class="text-5xl md:text-7xl font-bold tracking-tight leading-[1.1] mb-10">
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>Find nearby</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-primary-50 rounded-2xl align-middle mx-1">
            <MosqueIcon className="w-6 h-6 md:w-8 md:h-8 text-primary-600" />
          </span>
          <span>mosques</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>and accurate</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-primary-50 rounded-2xl align-middle mx-1">
            <ClockIcon className="w-6 h-6 md:w-8 md:h-8 text-primary-600" />
          </span>
          <span>prayer</span>
        </div>
        <div class="flex flex-wrap justify-center items-center gap-x-3 gap-y-2">
          <span>times in</span>
          <span class="inline-flex items-center justify-center w-12 h-12 md:w-16 md:h-16 bg-primary-50 rounded-2xl align-middle mx-1">
            <LocationIcon className="w-6 h-6 md:w-8 md:h-8 text-primary-600" />
          </span>
          <span>real-time</span>
        </div>
      </h1>

      <div class="mb-8">
        <Button>
          <Apple className="w-5 h-5" />
          <span class="text-base">Download for iOS</span>
        </Button>
      </div>

      <p class="text-sm text-gray-500 max-w-md">
        Starting with Leicestershire, connecting UK Muslims to their local mosques
      </p>
    </section>

    <!-- Phone Showcase -->
    <section class="w-full max-w-[1000px] px-4 mb-24 relative flex justify-center">
      <!-- Background glow/shadow simulation -->
      <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-gray-100/50 rounded-full blur-3xl -z-10"></div>
      
      <!-- Phone Container -->
      <!-- Since we don't have the hand image, we'll present the phone UI in a nice frame -->
      <div class="relative w-[300px] md:w-[340px] h-[680px] md:h-[720px] transition-transform hover:scale-[1.02] duration-500">
        <PhoneUI />
      </div>
    </section>

    <!-- Community Showcase -->
    <section class="w-full max-w-6xl mx-auto px-6 pb-24">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="relative overflow-hidden rounded-3xl aspect-[4/5] bg-gray-100">
          <img 
            src="/generated/image-a-young-british-muslim-man-in-his-20s-lo-1765752420593-0.webp" 
            alt="Unity Hub user finding nearby mosques"
            class="w-full h-full object-cover"
          />
        </div>
        <div class="relative overflow-hidden rounded-3xl aspect-[4/5] bg-gray-100">
          <img 
            src="/generated/image-close-up-of-hands-holding-a-modern-smart-1765752428472-3.webp" 
            alt="Using Unity Hub for prayer times"
            class="w-full h-full object-cover"
          />
        </div>
      </div>
    </section>

    <!-- Mosque Showcase -->
    <section class="w-full max-w-6xl mx-auto px-6 pb-24">
      <div class="relative overflow-hidden rounded-3xl aspect-video bg-gray-100">
        <img 
          src="/generated/image-beautiful-exterior-of-a-traditional-mosq-1765752423561-1.webp" 
          alt="Leicester mosque"
          class="w-full h-full object-cover"
        />
      </div>
    </section>

    <!-- Features Text -->
    <section class="max-w-4xl mx-auto px-6 pb-32 space-y-24 text-center">
      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Unity Hub is your comprehensive mosque directory with real-time prayer times, helping you stay connected to your faith wherever you are
        </h3>
      </div>

      <div class="space-y-6">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Discover mosques near you with accurate distances, addresses, and up-to-date prayer schedules for all five daily prayers
        </h3>
      </div>

      <div class="space-y-10">
        <h3 class="text-3xl md:text-5xl font-bold tracking-tight leading-tight">
          Built for the UK Muslim community, Unity Hub overcomes the fragmentation of mosque information with a centralized, location-based platform
        </h3>
        
        <div class="pt-4">
          <Button>
            <Apple className="w-5 h-5" />
            <span class="text-base">Download for iOS</span>
          </Button>
        </div>
      </div>
    </section>

    <!-- Community Image -->
    <section class="w-full max-w-6xl mx-auto px-6 pb-32">
      <div class="relative overflow-hidden rounded-3xl aspect-video bg-gray-100">
        <img 
          src="/generated/image-diverse-group-of-british-muslim-families-1765752425980-2.webp" 
          alt="Muslim community in Leicester"
          class="w-full h-full object-cover"
        />
      </div>
      <p class="text-center text-gray-500 text-sm mt-6 max-w-2xl mx-auto">
        Bringing together the UK's 3.9 million Muslims through a unified platform, starting with Leicestershire's vibrant Muslim community
      </p>
    </section>

    <!-- Footer -->
    <footer class="w-full py-12 flex flex-col items-center gap-6 text-center border-t border-gray-100 mt-auto">
      <div class="flex items-center gap-2">
        <svg width="24" height="24" viewBox="0 0 96 95" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M65.5946 30.0964C73.7657 38.2675 79.5137 47.2795 82.2155 55.226C84.9288 63.2063 84.5245 69.9453 80.6881 73.7817C76.8516 77.6182 70.1126 78.0225 62.1323 75.3092C54.1858 72.6074 45.1738 66.8594 37.0027 58.6883C28.8317 50.5173 23.0837 41.5053 20.3819 33.5588C17.6686 25.5784 18.0728 18.8395 21.9093 15.003C25.7458 11.1665 32.4847 10.7623 40.4651 13.4756C48.4116 16.1774 57.4236 21.9254 65.5946 30.0964Z" stroke="currentColor" stroke-width="2"/>
          <path d="M59.3798 36.3116C67.5508 44.4827 73.2988 53.4947 76.0006 61.4412C78.714 69.4216 78.3097 76.1605 74.4732 79.997C70.6367 83.8334 63.8978 84.2377 55.9174 81.5244C47.971 78.8226 38.9589 73.0746 30.7879 64.9035C22.6169 56.7325 16.8688 47.7205 14.167 39.774C11.4537 31.7936 11.858 25.0547 15.6945 21.2182C19.5309 17.3817 26.2699 16.9775 34.2502 19.6908C42.1967 22.3926 51.2088 28.1406 59.3798 36.3116Z" stroke="currentColor" stroke-width="2"/>
        </svg>
        <div class="font-bold text-xl tracking-tight text-gray-200">Unity Hub</div>
      </div>
      <div class="flex flex-wrap justify-center gap-4 text-xs text-gray-400 font-medium">
        <a href="#" class="hover:text-black transition-colors">App Store</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Contact</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Support</a>
        <span>•</span>
        <a href="#" class="hover:text-black transition-colors">Privacy Policy</a>
      </div>
      <div class="text-[10px] text-gray-300">
        Connecting UK Muslims to their local mosques
      </div>
    </footer>
  </main>
</div>


