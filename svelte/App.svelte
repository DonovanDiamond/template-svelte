
<script>
    import Example from "./pages/Example.svelte";
    let name
</script>

<main>
    <Example {name} />
    <label>Enter name:
        <input type="text" bind:value={name}>
    </label>
</main>
