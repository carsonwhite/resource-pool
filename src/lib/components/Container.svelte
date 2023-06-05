<script lang="ts">
	export let w: number;
	export let h: number;

	//TODO: have types of basic containers, text editors, image galleries, embedded videos etc...
	// export let type: string;
</script>

<div class="border-2 border-black bg-gray-500 w-min">
	<textarea name="main" id="main" cols={w} rows={h} />
</div>
