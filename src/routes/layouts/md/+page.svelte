<script lang="ts">
  export let title = 'Dillshare';
</script>

<svelte:head>
  <title>{title}</title>
</svelte:head>

<div class="py-12 text-white">
  <article class="prose prose-invert mx-auto max-w-7xl px-6 lg:px-8">
    <slot />
  </article>
</div>
