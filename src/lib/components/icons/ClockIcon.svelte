<script lang="ts">
  export let className = "w-6 h-6 inline-block align-text-bottom";
</script>

<svg viewBox="0 0 24 24" fill="currentColor" class={className} xmlns="http://www.w3.org/2000/svg">
  <!-- Clock circle -->
  <circle cx="12" cy="12" r="9" stroke="currentColor" stroke-width="2" fill="none"/>
  <!-- Hour hand -->
  <path d="M12 12L12 8" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
  <!-- Minute hand -->
  <path d="M12 12L15 12" stroke="currentColor" stroke-width="2" stroke-linecap="round"/>
  <!-- Center dot -->
  <circle cx="12" cy="12" r="1.5" fill="currentColor"/>
</svg>
