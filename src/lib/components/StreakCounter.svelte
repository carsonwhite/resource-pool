<script lang="ts">
	export let id;
	export let data;
	console.log(id, data);

	let dummyData = {
		'2022-02-13': 200,
		'2022-02-14': 250,
	};
</script>

<div>
	<h1>Streak Counter</h1>
	<form>
		{#each dummyData as day, index}
			<input type="number" name="" id="" placeholder="1" />
		{/each}
	</form>
</div>
