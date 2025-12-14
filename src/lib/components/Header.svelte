<script lang="ts">
  import Button from './Button.svelte';
  import Apple from './icons/Apple.svelte';
</script>

<header class="w-full max-w-[1200px] mx-auto px-6 py-6 flex items-center justify-between">
  <div class="flex items-center gap-3">
    <svg width="32" height="32" viewBox="0 0 96 95" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M65.5946 30.0964C73.7657 38.2675 79.5137 47.2795 82.2155 55.226C84.9288 63.2063 84.5245 69.9453 80.6881 73.7817C76.8516 77.6182 70.1126 78.0225 62.1323 75.3092C54.1858 72.6074 45.1738 66.8594 37.0027 58.6883C28.8317 50.5173 23.0837 41.5053 20.3819 33.5588C17.6686 25.5784 18.0728 18.8395 21.9093 15.003C25.7458 11.1665 32.4847 10.7623 40.4651 13.4756C48.4116 16.1774 57.4236 21.9254 65.5946 30.0964Z" stroke="black" stroke-width="2"/>
      <path d="M59.3798 36.3116C67.5508 44.4827 73.2988 53.4947 76.0006 61.4412C78.714 69.4216 78.3097 76.1605 74.4732 79.997C70.6367 83.8334 63.8978 84.2377 55.9174 81.5244C47.971 78.8226 38.9589 73.0746 30.7879 64.9035C22.6169 56.7325 16.8688 47.7205 14.167 39.774C11.4537 31.7936 11.858 25.0547 15.6945 21.2182C19.5309 17.3817 26.2699 16.9775 34.2502 19.6908C42.1967 22.3926 51.2088 28.1406 59.3798 36.3116Z" stroke="black" stroke-width="2"/>
    </svg>
    <div class="font-bold text-xl tracking-tight">Unity Hub</div>
  </div>
  <Button>
    <Apple className="w-4 h-4" />
    <span>Download for iOS</span>
  </Button>
</header>
