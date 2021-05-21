<script>
    export let something;
</script>

{#if something}
    <p>{something}</p>
{:else}
    <p>Some text</p>
{/if}
