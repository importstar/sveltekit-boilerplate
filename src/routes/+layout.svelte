<script lang="ts">
    import type { Snippet } from 'svelte';
    import type { LayoutData } from './$types';
    import "$lib/app.css";

    let { data, children }: { data: LayoutData, children: Snippet } = $props();
</script>

{@render children()}