<script>
    import Network from "../network.svelte";
</script>

{#each [{ name: "Home", url: "/" }, { name: "Dexscreener", url: "https://dexscreener.com" }, { name: "Twitter", url: "https://x.com" }, { name: "Discord", url: "https://discord.com" }] as { name, url }}
    <a
        href={url}
        data-sveltekit-reload
        class="btn-ghost btn w-full">{name}</a
    >
{/each}
<Network />
