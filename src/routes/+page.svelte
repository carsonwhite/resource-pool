<script>
	import Container from '~components/Container.svelte';
	import StreakCounter from '~components/StreakCounter.svelte';

	console.log('hello');

	let firstContainer = {
		h: 10,
		w: 20,
	};
</script>

<div class="bg-blue-200 min-h-screen">
	<!-- <Container {...firstContainer} /> -->
	<StreakCounter id="1" data="[]" />
</div>
