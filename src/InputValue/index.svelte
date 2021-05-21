<script>
    let inputVal = 0;
    const handleClick = () => {
        inputVal++;
    }
</script>

<div>
    <input type="text" value={inputVal} disabled/>
    <button on:click={handleClick}>+</button>
</div>
