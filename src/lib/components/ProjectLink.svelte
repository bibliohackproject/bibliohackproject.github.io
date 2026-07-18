<script lang="ts">
  let {
    name,
    url,
    description,
    developer,
    icon,
    image,
  }: {
    name: string;
    url: string;
    description?: string;
    developer?: string;
    icon?: string;
    image?: string;
  } = $props();
</script>

<a href={url} target="_blank" rel="noopener noreferrer" class="inline-flex">
  <div class="border border-slate-900 p-8 flex flex-col gap-2">
    {#if image}
      <img src={image} alt={name} class="w-full object-cover" />
    {/if}
    <div class="inline-flex items-center gap-1">
      {#if icon}
        <img src={icon} alt="" class="size-5" />
      {/if}
      {name}
    </div>
    {#if description}
      <p class="text-sm">{description}</p>
    {/if}
    {#if developer}
      <p class="text-xs text-slate-500">{developer}</p>
    {/if}
  </div>
</a>
