
<script>
	import { TextBox,TextBlock,ToggleSwitch } from "fluent-svelte";
</script>

<h1>The OA</h1>
<TextBox placeholder="TextBox" />
<ToggleSwitch checked />

<style>
    @import url("https://unpkg.com/fluent-svelte/theme.css");

    /* Some base styles to get things looking right. */
    :global(body) {
        background-color: var(--fds-solid-background-base);
        color: var(--fds-text-primary);
    }
</style>