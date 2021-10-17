<script>
    import Color from '$lib/Color.svelte';
    let colorName = 'Pink';
    let colorName2 = 'Blue';
</script>

<div>
    <h1 class="text-primary">Play with Colors</h1>
</div>

<div>
    <input bind:value={colorName} />
    <input bind:value={colorName2} />
    <Color color={colorName} />
    <Color color={colorName2}/>
</div>

<style>
    input {
   	 padding: 0.5em;
   	 text-align: center;
    }
    div {
   	 text-align: center;
   	 margin: 3em auto;
    }
</style>