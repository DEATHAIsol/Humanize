<script>
    import Icon from "$lib/components/icon.svelte";
</script>

<footer
    class="footer mt-0 grid w-full grid-cols-2 items-center border bg-black p-3"
>
    <div class="col-span-1 flex items-center">
        <!-- PoweredByHelius removed -->
    </div>

    <div class="col-span-1 flex w-full justify-end">
        <div class="mr-12">
            <a
                href="https://discord.com"
                class="btn-ghost btn"
            >
                <Icon
                    id="discord"
                    size="md"
                />
            </a>
            <a
                href="https://x.com"
                class="btn-ghost btn"
            >
                <Icon
                    id="twitter"
                    size="md"
                />
            </a>
        </div>
    </div>
</footer>
