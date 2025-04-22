<script>
  import '$lib/styles/tailwind.postcss';
</script>

<!-- hared layout structure -->
<div class="min-h-screen bg-gray-50">
  <slot /> <!-- This renders +page.svelte content -->
</div>