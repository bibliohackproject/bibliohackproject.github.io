<script lang="ts">
  import type { SimpleIcon } from "simple-icons";

  let { icon, class: className = "" }: { icon: SimpleIcon; class?: string } =
    $props();
</script>

<svg viewBox="0 0 24 24" fill="currentColor" class={className} aria-hidden="true">
  <path d={icon.path} />
</svg>
