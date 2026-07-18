<script lang="ts">
  import ExternalLink from "@lucide/svelte/icons/external-link";

  let { name, url }: { name: string; url: string } = $props();
</script>

<a href={url} target="_blank" rel="noopener noreferrer" class="inline-flex">
  <div class="border border-slate-900 p-8 inline-flex items-center gap-1">
    {name}<ExternalLink class="size-4" />
  </div>
</a>
