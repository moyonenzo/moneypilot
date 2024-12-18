<script lang="ts">
	import History from "$lib/directives/history/index.svelte";
	import Stats from "$lib/directives/stats/index.svelte";
</script>

<main class="flex w-full h-screen justify-center items-center">
	<div class="flex flex-row w-full h-3/4 justify-center items-center gap-5">
		<Stats />
		<History />
	</div>
</main>
