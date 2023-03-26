<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	<ul>
	{#if clicked == true} <a href='You have clicked the button!'></a>
	{:else} <a href='You have to click the button!></a>
	{/if}
	</ul>
</div>
